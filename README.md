# Earthquake-Time-Series-Anomaly-Detection
# Earthquake Time-Series Anomaly Detection

Milestone 2: https://colab.research.google.com/drive/1Ec5pKxrcRO1LiQqI-zKskfMPQbWtk48T#scrollTo=PvNlThz4AYoV
Milestone 3: https://colab.research.google.com/drive/1q-2y5poIYWL_w4HnD_1v7EfIo33MgVVg#scrollTo=install-libs

---

## 📖 Overview

Earthquakes generate seismic waves that travel through the Earth's surface and are recorded continuously by seismic monitoring stations. Detecting abnormal seismic activity from these time-series signals is essential for disaster monitoring, early warning systems, and seismic risk analysis.

This project presents a deep learning-based Earthquake Time-Series Anomaly Detection system using LSTM Autoencoder networks. The system learns normal seismic behavior patterns from historical earthquake datasets and identifies anomalies using reconstruction error analysis.

The project also includes a Gradio-based interactive dashboard that allows users to input seismic parameters such as latitude, longitude, depth, magnitude, and RMS values for real-time anomaly prediction and visualization.

---

## ✨ Key Features

- Earthquake anomaly detection using deep learning
- Time-series seismic data analysis
- LSTM Autoencoder implementation
- Reconstruction error-based anomaly detection
- Exploratory Data Analysis (EDA)
- Hyperparameter tuning and model optimization
- Real-time anomaly prediction
- Interactive Gradio dashboard deployment
- Earthquake trend and geographic visualization

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Deep Learning Framework
- TensorFlow
- Keras

### Data Processing
- Pandas
- NumPy

### Machine Learning Utilities
- Scikit-learn

### Data Visualization
- Matplotlib
- Seaborn
- Plotly

### Deployment Framework
- Gradio

---

## 📂 Repository Structure

```text
Earthquake-Time-Series-Anomaly-Detection/
│
├── notebooks/
│   ├── 01_Data_Preprocessing_and_EDA.ipynb
│   ├── 02_LSTM_Autoencoder_Model.ipynb
│   └── 03_Gradio_Dashboard.ipynb
│
├── models/
│   ├── earthquake_lstm_autoencoder.h5
│   ├── scaler.pkl
│   └── config.pkl
│
├── screenshots/
│   ├── dashboard_interface.png
│   ├── anomaly_detection.png
│   └── training_loss.png
│
├── app.py
├── requirements.txt
├── Project_Report.pdf
└── README.md
```

---

## 📊 Dataset Information

The dataset used in this project contains historical earthquake and seismic records collected from publicly available seismic databases.

### Dataset Sources
- USGS Earthquake Catalog
- IRIS Seismic Data Archives

### Features Used
- Latitude
- Longitude
- Depth
- Magnitude
- RMS Value

### Data Preprocessing Steps
- Missing value handling
- Data normalization using MinMaxScaler
- Time-series sequence generation
- Sliding window transformation
- Feature selection and scaling

---

## 🧠 Deep Learning Model

### LSTM Autoencoder

The project uses an LSTM Autoencoder architecture for unsupervised anomaly detection in seismic time-series data.

### Model Architecture
- Encoder LSTM layers
- RepeatVector layer
- Decoder LSTM layers
- TimeDistributed output layer

The model learns normal seismic patterns and reconstructs the input sequence. Anomalies are detected when reconstruction error exceeds a predefined threshold.

---

## 📈 Model Evaluation

The system evaluates anomaly detection performance using reconstruction error analysis and visualization techniques.

### Evaluation Methods
- Reconstruction Loss
- Threshold-based anomaly detection
- Training vs Validation Loss
- Error distribution analysis

### Visualization
- Earthquake magnitude trends
- Time-series seismic analysis
- Anomaly detection graphs
- Geographic earthquake mapping
- Correlation heatmaps

---

## 🚀 Gradio Dashboard

The project includes an interactive Gradio web application for real-time earthquake anomaly detection.

### Dashboard Features
- Editable seismic input table
- Real-time anomaly prediction
- Magnitude trend visualization
- Depth distribution charts
- Geographic earthquake mapping
- Prediction status display

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Earthquake-Time-Series-Anomaly-Detection.git
```

Move into the project directory:

```bash
cd Earthquake-Time-Series-Anomaly-Detection
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch the Gradio dashboard:

```bash
python app.py
```

---

## 📌 Requirements

Create a `requirements.txt` file with the following libraries:

```text
tensorflow
keras
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
gradio
joblib
```

---

## 📷 Output Screenshots

### Dashboard Interface
Interactive earthquake anomaly detection dashboard.

### Model Training
Training and validation loss visualization.

### Anomaly Detection Results
Detected seismic anomalies using reconstruction error.

---

## 🔮 Future Improvements

- Integration with live seismic APIs
- Real-time earthquake monitoring
- Cloud deployment support
- Automated emergency alert systems
- Transformer-based anomaly detection models
- Advanced explainable AI techniques
- IoT-based seismic sensor integration

---

## 📚 Conclusion

This project demonstrates the practical implementation of deep learning techniques for earthquake anomaly detection using time-series seismic data. The LSTM Autoencoder effectively identifies abnormal seismic behavior through reconstruction error analysis and sequential learning.

The Gradio-based dashboard further enhances usability by providing a real-time, interactive platform for seismic monitoring, anomaly prediction, and earthquake visualization.

---

## 👨‍💻 Author

Dinesh

---

## 📄 License

This project is developed for educational and research purposes.
