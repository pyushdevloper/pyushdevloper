- 👋 Hi, I’m @pyush android devloper
- 👀 I’m interested in android os ...
- 🌱 I’m currently working in ppui,vb meta...
- 💞️ I’m looking to collaborate on ppui ...
- 📫 How to reach me😂, ...
- 😁 if you want to collaborate-dm on instagram
<!---
pyushdevloper/pyushdevloper is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
In [12]: # Wrapping the vectors in NumPy arrays
In [13]: input_vector = np.array([1.66, 1.56])
In [14]: weights_1 = np.array([1.45, -0.66])
In [15]: bias = np.array([0.0])

In [16]: def sigmoid(x):
   ...:     return 1 / (1 + np.exp(-x))

In [17]: def make_prediction(input_vector, weights, bias):
   ...:      layer_1 = np.dot(input_vector, weights) + bias
   ...:      layer_2 = sigmoid(layer_1)
   ...:      return layer_2

In [18]: prediction = make_prediction(input_vector, weights_1, bias)

In [19]: print(f"The prediction result is: {prediction}")
Out[19]: The prediction result is: [0.7985731]
