# Retention-Modelling-using-Classification-algorithms
Classification of retention membership model of a travel company. Case study of university of Virginia

**Models Used:**
- **Random Forest**: 
- **XGBoost**:
- **Logistic Regression**:
- **CART**: 

Based on the analysis of the provided case studies and the Jupyter Notebooks, here's a detailed README file focusing on the models and the story of David Powell's journey:

---

# Retention Modeling at Scholastic Travel Company

This repository contains two interconnected stories focusing on customer retention modeling for Scholastic Travel Company (STC), an educational tourism firm. The stories follow the journey of David Powell, a new data analyst, as he navigates through building and improving predictive models to help STC enhance their customer retention strategies.

## Story Overview

### Story Part A: The Initial Challenge
David Powell, newly hired at STC, is eager to make an impact. He is tasked with his first major project: developing a predictive model to forecast which customers will rebook with STC for the next school year. Armed with past trip data and customer information, David sets out to create a model that can accurately identify potential returning customers.

**Key Highlights:**
- David's initial days at STC and his eagerness to contribute.
- The urgency conveyed by his supervisor, Stephen Blackford, to develop a retention model.
- David's process of analyzing available data and constructing the initial predictive model.

### Story Part B: The Improvement
After presenting his initial model, David engages in a conversation with Emily Glenn, an analyst at STC. She introduces him to additional data sources, including Net Promoter Scores (NPS) and group formation timings, which hold potential to improve his model's accuracy. David incorporates this new data, tackling challenges along the way, and refines his model to better predict customer retention.

**Key Highlights:**
- David's interaction with Emily Glenn and the discovery of new valuable data.
- The excitement and challenges of integrating NPS and group formation data.
- The process of enhancing the predictive model to achieve better accuracy.

**Models Used:**
- **Random Forest**: 
- **XGBoost**:
- **RandomForestClassifier**:
- **CART**: 





## How to Use

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/retention-modeling-stc.git
   cd retention-modeling-stc
   ```

2. **Explore the Stories:**
   - Review the documents in the root directory to follow David Powell's journey.
   - Understand the context and objectives of each part.

3. **Data Analysis and Modeling:**
   - Navigate to the `models` directory.
   - Open and run the Jupyter Notebooks to explore the data, build, and evaluate the models.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- XGBoost
- mlxtend

Final Results ( AUC curve which tells about the efficiency of the model across all possible thresholds)
Logistic Regression
![image](https://github.com/user-attachments/assets/8b7b3fc7-367d-4d33-bdc2-8fe92352a887)

CART
![image](https://github.com/user-attachments/assets/6a4437e8-ec20-4319-bfd8-a9fdc90b2dca)

Random Forest
![image](https://github.com/user-attachments/assets/a08893b2-e0f1-4fa5-8c55-e4eecab0659f)

XGBoost
![image](https://github.com/user-attachments/assets/6001a28c-0752-4598-bf20-8c91a8d2a7d3)

Stepwise Logit
![image](https://github.com/user-attachments/assets/6da9ac5b-31b2-48cf-b758-d463fdca98ef)

**Results**
XG boost has the higest accuracy and the usage of the model depends on different scenarios taking it's limitation into consideration.Here the features might not be linearly dependent , means they might be non linear, therefore XGBoost considers non linearity and are the best to use.



## Contact

For any questions or suggestions, please feel free to reach out via email: pruthvib@uci.edu
