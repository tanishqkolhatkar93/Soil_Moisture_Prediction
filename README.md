

# 🌱 Soil Moisture Prediction using Remote Sensing Data

## 📌 Project Overview  
This project aims to predict soil moisture levels using remote sensing satellite data. Various deep learning models, including **LSTM, BiLSTM, and GRU**, were tested to achieve optimal accuracy.

## 📊 Dataset  
- **Source**: [Specify the dataset source, e.g., NASA SMAP, Sentinel-1, MODIS, or in-situ data]  
- **Features**: Includes temperature, precipitation, vegetation index (NDVI), soil type, and satellite-based moisture estimates.  
- **Preprocessing**: Data normalization, handling missing values, feature selection.  

## 🏗️ Model Architecture  
- **LSTM**: Achieved **70% accuracy**  
- **BiLSTM**: Achieved **53% accuracy**  
- **GRU**: Achieved **46% accuracy**  
- **Loss Function**: [Specify, e.g., MSE]  
- **Optimizer**: [Specify, e.g., Adam]  

## 🚀 Implementation Steps  
1. **Data Collection & Preprocessing**  
2. **Feature Engineering & Selection**  
3. **Model Training & Hyperparameter Tuning**  
4. **Evaluation & Performance Comparison**  
5. **Deployment (if applicable)**  

## 📈 Results & Findings  
- LSTM outperformed BiLSTM and GRU, achieving the highest accuracy.  
- Remote sensing features significantly impact prediction accuracy.  

## 📌 Future Improvements  
- Experimenting with **Transformer-based models**.  
- Integrating **ground-truth soil moisture** data for better validation.  
- Deploying a **real-time prediction system**.  

## 🛠️ Technologies Used  
- Python (TensorFlow, Keras, PyTorch)  
- Remote Sensing Libraries (Rasterio, GDAL)  
- Data Processing (Pandas, NumPy)  
- Visualization (Matplotlib, Seaborn)  
