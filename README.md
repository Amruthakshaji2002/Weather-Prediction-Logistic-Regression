# 🌦️ Weather Prediction using Logistic Regression  

A machine learning project that predicts **Rain**, **Sun**, or **Snow** based on meteorological data such as maximum temperature, minimum temperature, and wind speed.  
The model is trained with Logistic Regression and deployed as a simple web application using Flask.  

---

## 📌 Project Overview  
Weather forecasting plays an important role in everyday life.  
Traditional methods rely on physical instruments and satellite data, but with the availability of large datasets, **machine learning models** can provide fast and accurate predictions.  

This project uses **Logistic Regression** to predict weather conditions from simple input parameters and demonstrates deployment through a Flask web application.  

---

## 🎯 Objectives  
- Build a Logistic Regression model to classify weather conditions.  
- Use a **One-vs-All** approach for multi-class classification (Rain vs Sun vs Snow).  
- Develop a simple and user-friendly **Flask web app** for predictions.  

---

## 📊 Dataset & Features  
- Input Factors:  
  - 🌡️ Maximum Temperature  
  - 🌡️ Minimum Temperature  
  - 🌬️ Wind Speed  

- Output Classes:  
  - 🌧️ Rain  
  - ☀️ Sun  
  - ❄️ Snow  

---

## 🧠 Methodology  
1. Preprocess dataset (train/test split)  
2. Train Logistic Regression model  
3. Save model using **pickle**  
4. Build Flask web app for predictions  
5. User enters input → model predicts → output shown on web page  

---

## 📈 Results  
- Model successfully classifies weather into **Rain, Sun, Snow**.  
- Accuracy improves with appropriate preprocessing and parameter tuning.  

<img src="https://github.com/Amruthakshaji2002/Weather-Prediction-Logistic-Regression/blob/main/prediction3.png" width="350">
<img src="https://github.com/Amruthakshaji2002/Weather-Prediction-Logistic-Regression/blob/main/prediction4.png" width="350">


---

## 💡 Advantages  
- ✅ User accessibility through web interface  
- ✅ Location-based forecasting possible with more features  
- ✅ Lightweight and fast model  

---

## 🔮 Future Scope  
- Improve accuracy by adding more meteorological parameters  
- Integrate real-time weather data APIs  
- Extend to mobile or cloud-based deployment  

---
