# Crop Recommendation System 🌱
#### An ML & DL–powered web application that suggests suitable crops, fertilizer usage, and detects plant diseases.

---

## ⚠️ Disclaimer
This project is a **proof of concept (POC)**. The datasets and predictions used in this application are not guaranteed to be fully accurate or certified. Hence, it should **not be used for real-world agricultural decision-making**.  
The purpose of this project is to demonstrate how **Machine Learning and Deep Learning can be applied to precision agriculture** when developed at scale with reliable and validated data sources.

---

## 💡 Motivation
- Agriculture plays a vital role in driving a nation’s economic development.  

- In a country like India, a large portion of the population depends on farming as their primary livelihood. With advancements in technology, **Machine Learning and Deep Learning** are increasingly being adopted to help farmers improve productivity and crop yield.  

- This project presents a web-based system that integrates three major agricultural applications:
  - **Crop Recommendation**
  - **Fertilizer Recommendation**
  - **Plant Disease Detection**

### Application Details
- **Crop Recommendation**:  
  Users provide soil nutrient values and location details. The system predicts the most suitable crop to cultivate under those conditions.

- **Fertilizer Recommendation**:  
  Based on soil nutrients and selected crop type, the system identifies nutrient deficiencies or excesses and suggests appropriate fertilizer usage.

- **Plant Disease Detection**:  
  Users upload an image of a plant leaf. The system predicts whether the plant is healthy or diseased and provides disease details along with preventive or corrective measures.

---

## 🛠️ Built With
- Python  
- HTML5, CSS3, JavaScript  
- Bootstrap  
- Flask  
- Git  
- Heroku  
- NumPy, Pandas  
- Matplotlib  
- Scikit-learn  
- PyTorch  

---

## 💻 How to Use

### 🌾 Crop Recommendation
- Enter soil nutrient values (N-P-K ratio), along with state and city.
- Ensure the city name is commonly recognized, as weather data is fetched using the **OpenWeather API**.
- Refer to this guide for understanding NPK ratios:  
  https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm  

---

### 🌱 Fertilizer Recommendation
- Input soil nutrient values and the crop you plan to grow.
- The system evaluates nutrient imbalance and provides fertilizer improvement suggestions.

---

### 🍃 Plant Disease Detection
- Upload an image of the affected plant leaf.
- The system predicts the crop type, disease status, cause, and preventive measures.

#### Currently Supported Crops
<details>
  <summary>View supported crops</summary>

- Apple  
- Blueberry  
- Cherry  
- Corn  
- Grape  
- Pepper  
- Orange  
- Peach  
- Potato  
- Soybean  
- Strawberry  
- Tomato  
- Squash  
- Raspberry  

</details>

---

## ⚙️ Run Locally

### Prerequisites
Ensure the following are installed:
- Git  
- Anaconda or Miniconda  

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/pavan1832/crop-recommendation-system.git
