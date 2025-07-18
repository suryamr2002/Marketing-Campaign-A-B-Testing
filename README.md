# 📊 Marketing Campaign Analysis using A/B Testing

This project performs a comprehensive **A/B Testing-based statistical analysis** of a marketing campaign to determine whether a personalized strategy is more effective than a generic approach. The analysis is done using Python and essential data science libraries, with detailed steps from data loading and cleaning to hypothesis testing and final business conclusions.

---

## 📌 Objective

The primary goal of this project is to:

- Evaluate the performance of two marketing strategies: **Control** (generic message) and **Personalization** (customized message).
- Use **statistical testing (A/B testing)** to determine if there is a significant difference in conversion rates between the two.
- Derive actionable insights for the marketing team based on statistical evidence.

---

## 🧾 Dataset Overview

The dataset simulates responses to two marketing campaigns sent to different customer segments.

- **Features include:**
  - `user_id`: Unique identifier for each participant.
  - `group`: Control or Personalization.
  - `converted`: Binary value indicating whether the user converted (1) or not (0).

---

## 🧪 Methodology

The project follows a structured data science approach:

### 1. **Data Exploration & Cleaning**
- Load the dataset.
- Check for missing or duplicate values.
- Perform basic statistics on conversion rates.

### 2. **Data Visualization**
- Visualize conversion distributions between control and personalization groups.
- Use bar plots and boxplots to compare performance.

### 3. **Hypothesis Testing**
- **Null Hypothesis (H₀):** There is no significant difference in conversion between Control and Personalization.
- **Alternative Hypothesis (H₁):** Personalization leads to higher conversion rates.
- Perform a **two-sample t-test** (independent) to validate hypotheses.

### 4. **Lift & statistical significance**
- Measure the **lift** in performance.
- Report **p-values** and **statistical significance**.

---

## 📉 Key Results

- **Conversion Rate (Control) for dependent factors** 
- **Conversion Rate (Personalization) for dependent factors**  
- **Lift: for dependent factors** 
- **Conclusion:** The personalization campaign performs **significantly better** than the generic campaign for each segment ( Email, Instagram, House ads, etc.)

---

## ⚙️ Technologies & Libraries Used

- **Python**
- **Pandas** – data manipulation
- **Matplotlib & Seaborn** – visualization
- **NumPy** – numerical operations
- **SciPy** – statistical testing

---

## 📚 Skills Applied

- A/B Testing
- Experimental Design
- Hypothesis Testing
- Data Cleaning & EDA
- Statistical Significance Analysis
- Visualization & Interpretation

---

## 📈 Business Implications

- Personalized marketing increases conversion and should be prioritized.
- A data-driven approach can guide campaign decisions and increase ROI.

---

## 📎 How to Run

1. Clone the repository:
   ```bash
   git gh repo clone suryamr2002/Marketing-Campaign-A-B-Testing
   ```

2. Launch Jupyter Notebook and open the `.ipynb` file:
   ```bash
   jupyter notebook
   ```

---

## 📬 Contact

**Author:** SURYA M.R
📧 [LinkedIn](https://www.linkedin.com/in/surya-m-r/)  
📂 [GitHub Portfolio](https://suryamr2002.github.io/)
