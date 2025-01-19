# Plant Disease Detection 🌱

Plant Disease Detection is a deep learning-based project aimed at helping farmers and agricultural researchers detect plant diseases efficiently. Using convolutional neural networks (CNNs) built with the PyTorch framework, this project classifies leaf images into 39 different categories. The model is trained on the **Plant Village Dataset**.

---

## 🌟 Features
- **Deep Learning Model**: Built using CNNs with PyTorch.
- **39 Disease Categories**: Comprehensive classification for common plant diseases.
- **Flask Web App**: Deployed using Flask for easy accessibility.
- **Interactive Jupyter Notebook**: Experiment with the model in a notebook environment.

---

## 📂 Dataset
We used the **Plant Village Dataset** for training the model. The dataset contains labeled images of plant leaves, ensuring accurate classification.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 installed on your machine.

### Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Plant-Disease-Detection.git
   cd Plant-Disease-Detection
2. **Create and Activate a Virtual Environment:**:
    ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. **Install Dependencies:**:
    ```bash
   pip install -r requirements.txt
4. **Download Pre-trained Model**: Download the pre-trained model file plant_disease_model_1.pt and place it in the App folder.
5. **Run the App**:
   ```bash
     python3 app.py

---

## 🧪 Testing the Model
- Use the test_images folder to test the model's predictions.
- Each image is labeled with its corresponding disease name for verification.
- For experimentation, you can use the Jupyter Notebook in the project to interact with the model.

---

## 🔧 Technologies Used
- Programming Language: Python 3.8
- Frameworks: PyTorch, Flask
- Deployment: Flask Web Application
- Dataset: Plant Village Dataset

---

## 📜 License
- This project is licensed under the MIT License.




