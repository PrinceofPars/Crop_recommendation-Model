# Crop Recommendation Model  

## Overview  
This repository contains an advanced **Crop Recommendation Model** that predicts the most profitable crops based on user inputs such as soil conditions, climate, and terrain type. The model enhances an existing dataset and provides personalized recommendations for farmers.  

## Dataset  
The dataset used for training the model is based on the **Kaggle Crop Recommendation Dataset**:  
[Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset?resource=download)  

Additional features were added to improve model accuracy and personalization, making recommendations more tailored to specific user conditions.  

## Project Integration  
This model is a crucial component of a larger agricultural project:  
[CropWise](https://github.com/vaibhavi0028/CropWise)  

It integrates with **CropWise** to provide smart crop recommendations based on economic and environmental factors.  

## Features  
- **Personalized Crop Recommendations**: Suggests crops based on **soil, climate, and terrain** conditions.  
- **Profit-Driven Approach**: Maximizes farmer profit by selecting the most lucrative crops.  
- **Soil Sustainability**: Ensures that recommended crops maintain soil fertility for long-term farming.  
- **Fertilizer Optimization**: Provides tailored fertilizer suggestions to enhance yield.  
- **Dynamic Pricing Integration**: Fetches real-time crop prices from an API.  
  - If the API is unavailable (between **10 PM and 6 AM**), it falls back to predefined crop prices.  
- **Supports 40 Crops**: The system currently provides recommendations for 40 different crops.  
- **JSON Output**: The model returns predictions in **JSON format**, making it easy to integrate into a frontend application.  

## Output Categories  
The model provides **two types of recommendations** based on the user’s terrain:  

1. **Hilly Terrain**  
   - Recommends **top 3 pairs of crops** to **maximize profit** and **prevent soil erosion**.  
2. **Plain Terrain (or Other Types)**  
   - Recommends **top 3 crops** to maximize profit while ensuring soil sustainability.  

## Future Enhancements  
- **Adding More Crops** to expand recommendation choices.  
- **Improving terrain-specific recommendations** for better adaptation.  

This project aims to assist farmers in making **data-driven decisions**, improving yield, and ensuring sustainable agriculture. 🚜🌱  

---
**Author**: *Prince*  
