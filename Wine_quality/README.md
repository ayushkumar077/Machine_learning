# 🍷 Wine Quality Checking with Neural Network

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ML-orange?logo=tensorflow)

<p align="center">
    <img src="Wine wine wine.jpeg" alt="Wine Banner" width="500px" height="340px">

</p>

---

## 🍇 About the Project

Welcome to the **Wine Quality Checking Neural Network**! This project uses a simple neural network to classify wine quality based on chemical properties. Whether you're a data science enthusiast, a wine lover, or just curious about machine learning, this project is for you! 🧑‍💻🍷

---

## 📊 Dataset
The dataset (`wines.csv`) contains 178 samples of wines with the following features:

- `alcohol`
- `malic_acid`
- `ash`
- `alcalinity_of_ash`
- `magnesium`
- `total_phenols`
- `flavanoids`
- `nonflavanoid_phenols`
- `proanthocyanins`
- `color_intensity`
- `hue`
- `OD280/OD315`
- `proline`
- `class` (target: 1, 2, or 3)

> ⚠️ Some values may be missing (NaN). For production, handle missing values appropriately.

---

## 🧠 Model Structure
- **Input:** 13 features
- **Dense Layer 1:** 4 units, ReLU
- **Dense Layer 2:** 5 units, ReLU
- **Output Layer:** 3 units, Softmax (for 3 wine classes)

---

## 🚀 Quick Start

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. **Install requirements:**
   ```bash
   pip install pandas numpy scikit-learn keras tensorflow seaborn
   ```
3. **Add the dataset:**
   - Place `wines.csv` in the project directory.
4. **Run the notebook:**
   - Open `wine_quality_check(NN).ipynb` in Jupyter Notebook or JupyterLab.
   - Run all cells to train and evaluate the model.

<p align="center">
  <img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="400" alt="Neural Network Training GIF">
</p>

---

## 📈 Output & Evaluation
After training, the notebook displays:
- ✅ **Accuracy**
- 📊 **Confusion Matrix**
- 📝 **Classification Report**
- 🔍 **First 10 predictions vs. true labels**

---

## 💡 Notes
- The model is trained and evaluated on the same data (no train/test split). For real-world use, split your data!
- Weights are initialized to zeros for demonstration. For better results, use default initializers.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests.

---

## 🐞 Issues
Found a bug or have a feature request? [Open an issue](https://github.com/Dhruv0126/Wine-Quality-Check//issues) and let's improve together!

---

## 📬 Contact
Made with ❤️ by **Dhruv Gupta**. Connect on [LinkedIn](https://www.linkedin.com/in/dhruvgupta0126/) or [GitHub](https://github.com/Dhruv0126/)!

---

<p align="center">
  <b>Cheers to learning and great wine! 🍷</b>
</p> 
