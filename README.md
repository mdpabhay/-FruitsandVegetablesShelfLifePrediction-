# -FruitsandVegetablesShelfLifePrediction-
# 🥬 AI-Based Shelf Life Prediction System for Fruits & Vegetables  
A Smart Monitoring System using Deep Learning, Computer Vision, and IoT to Predict and Extend the Shelf Life of Perishable Produce

---

## 📌 Project Overview  
This project presents a real-time, AI-powered monitoring system that accurately predicts the shelf life and freshness of fruits and vegetables using visual and environmental data. By combining machine learning with IoT sensors, it helps reduce food wastage, optimize storage, and promote sustainability throughout the agricultural supply chain.

---

## 🚀 Key Features  

- 🔍 RGB & Thermal Image Analysis using Convolutional Neural Networks (CNNs)  
- 📡 Real-time Monitoring of Environmental Conditions (Temperature, Humidity, Ethylene, etc.)  
- 🔁 Transfer Learning for accurate prediction on small and imbalanced datasets  
- 📈 Remaining Useful Life (RUL) Prediction with Confidence Intervals using Bayesian Neural Networks  
- 🌡️ NIR Spectroscopy-based Internal Quality Assessment (Moisture, Sugar, Acidity)  
- 📊 Dynamic Dashboard for Real-Time Alerts & Visualizations  
- 🌍 Designed to combat food wastage and enable smart agriculture

---

## 🧠 Technologies Used  

- 🐍 Python, TensorFlow / PyTorch, OpenCV  
- 🧠 Deep Learning (CNNs, Transfer Learning, BNNs)  
- 🦢 Sensor Data: DHT11, MQ-135 (Ethylene), Thermal Cameras  
- 📊 Visualization: Matplotlib, Plotly, Streamlit / Flask (for UI)  
- 📀 SQLite / CSV / JSON for data storage

---

## 📂 Project Structure

```
🔹 data/                # Images and environmental logs
🔹 models/              # Trained models (.h5/.pt)
🔹 src/                 # Source code (training, prediction, utils)
🔹 notebooks/           # Jupyter notebooks for EDA & prototyping
🔹 dashboard/           # Streamlit or Flask-based dashboard
🔹 requirements.txt     # Python dependencies
🔹 README.md            # Project overview
```

---

## ⚙️ Setup Instructions  

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/fruit-shelf-life-predictor.git
   cd fruit-shelf-life-predictor
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Connect hardware sensors or use sample datasets in /data folder  
4. Run prediction script  
   ```bash
   python src/predict_shelf_life.py
   ```

5. Launch dashboard  
   ```bash
   streamlit run dashboard/app.py
   ```

---

## ✅ Use Case Benefits  

- 👨‍🌾 Farmers: Accurate harvest and handling recommendations  
- 🚚 Distributors: Minimized spoilage during transit and warehousing  
- 🛒 Retailers: Smart inventory management and rotation  
- 🏠 Consumers: Fresher produce and reduced household waste  
- 🌱 Environment: Less methane emission, better use of resources

---

## 🧽 Future Enhancements  

- ✅ Mobile app integration for farmers and vendors  
- ✅ Hyperspectral Imaging support  
- ✅ Cloud deployment for global access  
- ✅ Integration with supply chain platforms

---

## 🤝 Contribution  
Contributions are welcome! Please fork this repo and submit a pull request for improvements or new features.

---

## 📄 License  
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments  
Special thanks to all researchers and contributors whose studies and models inspired this project.

