# 🏵️ Batik Banyumasan 🏺

## 📌 Overview
This project examines the effectiveness of deep learning in classifying **Batik Banyumasan** patterns. It compares a custom **CNN** and the pre-trained **VGG16** model, incorporating **Canny Edge Detection** to enhance feature extraction. The study aims to improve classification accuracy, providing insights into the role of edge detection in deep learning while supporting cultural preservation and automated batik recognition.

You can read **the document** of this project in [IEEE Xplore®](https://doi.org/10.1109/COMNETSAT63286.2024.10862216).

---

## 📂 Projects Structure
```
🧩 Batik-Banyumasan
├── 📄 Batik Banyumasan.ipynb			# Jupyter Notebook for model training
├── 🖼 Batik Banyumasan/              		# Dataset folder
├── 📸 Augmentation Process/			# Image augmentation notebook 
├── 🏗 M1.h5                          		# Trained CNN model
├── 🏗 M2.h5                          		# Trained CNN model
├── 🏗 M3.h5                          		# Trained CNN model
├── 🏗 M4.h5                          		# Trained CNN model
├── 🏗 VGG16_1.h5                          	# Trained VGG16 model
├── 🏗 VGG16_2.h5                          	# Trained VGG16 model
├── 🖼 Image Test (Download)/        		# Sample images for testing
```

---

## 📊 Dataset
The dataset consists of **Batik Banyumasan motifs** categorised into 11 types:
- 🏵 **Angguran**
- 🐓 **Ayam Puger**
- 🌿 **Jahe Lumbon**
- 🌱 **Jahe Puger**
- 🍃 **Jahe Srimpang**
- 🌾 **Lumbon**
- 🍯 **Madu Bronto**
- 🎋 **Pring Sedapur**
- 🏡 **Puger Galar**
- 🔺 **Puger Telu Bal**
- 🌳 **Wit Lumbon**

The dataset is available for download via **Mendeley Data**:
🔗 [Batik Banyumasan](https://doi.org/10.17632/vsjrkhs9km.2)

---

## 📌 Project Workflow
1. **Data Collection & Preprocessing** 🚧
   - 📸 Gather images manually
   - 🖼 Organize images into labelled subfolders
   - 🔄 Augment images to enhance dataset variability
2. **Feature Extraction** 🎭
   - ✨ Apply **Canny Edge Detection** for enhanced features
3. **Model Training & Evaluation** 🧠
   - 🚀 Train a **CNN model** and a **VGG16 model** using TensorFlow/Keras
   - 📏 Compare classification accuracy and performance
4. **Model Testing** 🏆
   - 🌐 Test model using separate data `Image Test (Download)`

---

## ✨ Features
✅ **Deep Learning for Batik Classification:**
   - 🏆 Uses **CNN & VGG16** for high-accuracy classification
   - ⚡ Integrates **Canny Edge Detection** for feature enhancement

✅ **Data Augmentation for Robust Learning:**
   - 🔍 Improves model generalisation
   - 📊 Handles variations in lighting, texture, and background

---

## 🛠 Technologies & Libraries
- 🐍 `Jupyter Notebook`
- 🔥 `TensorFlow` and `Keras`
- 🥨 `Albumentations`
- 📊 `Pandas` and `NumPy`
- 📈 `Matplotlib` and `Seaborn` 
- 🌐 `Sklearn`
- 🔍 `OpenCV` (for Canny Edge Detection)

---

## 📥 Installation
To run this project locally:

1️⃣ Clone this repository:
```sh
$ git clone https://github.com/mrzlsyf/Batik-Banyumasan.git
$ cd Batik-Banyumasan
```
2️⃣ Install Dependencies.

3️⃣ Download the dataset from [Mendeley Data](https://doi.org/10.17632/vsjrkhs9km.2) and place it in the `Batik Banyumasan/` folder.

---

## 🚀 Usage
1. 📂 **Load Data:** Ensure `Batik Banyumasan/` is correctly structured.
2. 🏃 **Run the Notebook:** Open `Batik Banyumasan.ipynb`.
3. 🖼 **Classify Batik:** Follow the notebook instructions to train and test the models.

---

## 📈 Results and Findings
🔹 **Key Insights:**
   - 📊 The CNN model achieved an accuracy of **94%** 
   - 🏆 The VGG16 model achieved an accuracy of **99%** 
   - 🎨 Canny Edge Detection improved feature representation for certain motifs 
   
🔹 **Applications in Industry:**
   - 🏺 Batik authentication and verification
   - 💡 AI-powered cultural heritage preservation
   - 🎭 Digital textile pattern recognition

---

## 🔮 Future Improvements
- ✨ Optimize model **architectures** for better accuracy
- 🔧 Improve classification accuracy with other **pre-trained models**
- 🔍 Add more **Batik categories** for broader classification
- 📊 Deploy as a **web-based** or **mobile application**

---

## 🤝 Contributing
Contributions are welcome! If you'd like to improve the project:
1. Fork the repository 🍴
2. Create a new branch 🌱
3. Make your improvements ✨
4. Submit a pull request 🔄

*🌟 If you love this project, don't forget to star ⭐ the repository and contribute! 🙌*

---

**💡 AI meets culture—empowering Batik classification through Deep Learning! 🚀**
