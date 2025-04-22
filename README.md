# Predict-plant-categories-based-on-environmental-preferences-and-watering-frequency
Predict plant categories based on environmental preferences and watering frequency
# 🌿 Plant Water Needs Classification

This project aims to classify plants based on environmental factors such as sunlight exposure, soil type, and watering frequency. Using a machine learning model, the project predicts whether a plant requires **low**, **medium**, or **high** water.

## 📂 Dataset
The dataset contains the following features:
- `sunlight_hours`: Average hours of sunlight per day
- `watering_freq_per_week`: Number of times the plant is watered per week
- `soil_type`: Type of soil (e.g., sandy, loamy, clay)
- `water_need`: Target variable (low, medium, high)

## ⚙️ Technologies Used
- Python
- scikit-learn
- pandas
- seaborn
- matplotlib
- Google Colab

## 🔍 Methodology
1. **Data Preprocessing**  
   - Handling missing values  
   - One-hot encoding of categorical features  
   - Feature scaling using `StandardScaler`

2. **Model Training**  
   - Trained a `Random Forest Classifier`  
   - Dataset split into 80% training and 20% testing  

3. **Evaluation**  
   - Accuracy, Precision, Recall, and F1-Score  
   - Confusion Matrix visualized with heatmap  

## 📊 Results
- The model achieved reasonable performance in classifying plant water needs.
- Confusion matrix helped visualize prediction errors and class balance.
  
## 📌 Usage
1. Clone the repository  
2. Upload your dataset (CSV format)  
3. Run the notebook or script to train and test the model  

## 📖 References
- [scikit-learn Documentation](https://scikit-learn.org/)
- [pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- Google Colab (for cloud-based execution)

## 🙌 Credits
- Dataset: Provided by faculty / custom-created  
- Guide: Online documentation and AI tools  
