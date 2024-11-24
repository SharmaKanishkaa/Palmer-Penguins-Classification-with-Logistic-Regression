# 🐧 Palmer Penguins Classification with Logistic Regression  

Welcome to the **Palmer Penguins Classification Project**! 🐧 This project uses the **Palmer Penguins dataset**, a delightful alternative to the Iris dataset, for building a **Logistic Regression model** from scratch.  

---

## 📋 **Dataset Overview**  

The dataset consists of measurements for three species of penguins observed in the Palmer Archipelago, Antarctica.  

### **Columns**  

| **Feature**            | **Description**                                |  
|-------------------------|-----------------------------------------------|  
| `species`              | Target variable: Penguin species (Adelie, Chinstrap, Gentoo). |  
| `island`               | Island of observation (Torgersen, Biscoe, Dream). |  
| `bill_length_mm`       | Length of the penguin's bill (in millimeters). |  
| `bill_depth_mm`        | Depth of the penguin's bill (in millimeters). |  
| `flipper_length_mm`    | Length of the penguin's flippers (in millimeters). |  
| `body_mass_g`          | Penguin's body mass (in grams). |  
| `year`                 | Year of observation. |  

---

## 📊 **Workflow**  

1. **Exploratory Data Analysis (EDA):**  
   - Visualized feature distributions to understand species differences.  
   - Identified strong correlations, particularly between features like `bill_length_mm`, `flipper_length_mm`, and `species`.  
   - Found distinct feature patterns for each species, making classification feasible.  

2. **Logistic Regression from Scratch:**  
   - Implemented the logistic regression algorithm manually to classify the penguin species.  
   - Used **Gradient Descent** for optimization and achieved **99% accuracy**.  

3. **Feature Standardization:**  
   - Standardized numerical features to improve model convergence and ensure balanced feature importance.  

---

## 🎯 **Results**  

| **Step**                  | **Outcome**      |  
|---------------------------|------------------|  
| EDA                       | Clear separability of classes based on features. |  
| Logistic Regression       | Implemented from scratch; achieved **99% accuracy**. |  
| Standardization           | Enhanced performance and convergence speed. |  

---

## 🛠️ **Tools and Techniques**  

- **Libraries Used:** `pandas`, `NumPy`, `Matplotlib`, `seaborn`  
- **Modeling:** Logistic regression manually implemented using Python  
- **Data Processing:** Feature standardization to ensure optimal performance  

---

## ✨ **Key Takeaways**  

- **EDA** was critical in uncovering feature importance and separability across penguin species.  
- Logistic Regression, even implemented from scratch, performed exceptionally well with proper standardization.  
