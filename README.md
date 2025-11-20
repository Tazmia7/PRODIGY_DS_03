# Decision Tree Classifier – Bank Marketing Dataset

This project builds a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit (`yes`/`no`) based on demographic and behavioral data.  

# Dataset
This dataset is a Bank Marketing dataset from the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

---

## 📂 Dataset Information

The dataset contains information collected from marketing campaigns of a Portuguese banking institution.

### **Target Variable**
- **Subscribed**: Whether the client subscribed to a term deposit  
  - 0 = No  
  - 1 = Yes  

### **Features**

Includes customer:

age : Integer Age

job : Occupation

marital : Marital Status

education : Education Level

default : has credit in default?

balance : average yearly balance in euros

housing : has housing loan?

loan : has personal loan?

contact : contact communication type

day_of_week : last contact day of the week

duration : last contact duration, in seconds (numeric)

campaign : number of contacts performed during this campaign and for this client

pdays : number of days that passed by after the client was last contacted from a previous campaign(numeric, -1 means client was not previously contacted)

previous : number of contacts performed before this campaign and for this client

poutcome : outcome of the previous marketing campaign

emp.var.rate: employment variation rate - quarterly indicator (numeric)

cons.price.idx: consumer price index - monthly indicator (numeric)

cons.conf.idx: consumer confidence index - monthly indicator (numeric)

euribor3m: euribor 3 month rate - daily indicator (numeric)

nr.employed: number of employees - quarterly indicator (numeric)

subscribed: has the client subscribed a term deposit? (outcome)

---

# Conclusion
In this project, we embarked on a journey to build a predictive model for term deposit subscriptions in a banking context to help a Portuguese banking institution tailor its marketing efforts effectively.

The duration of calls was a significant predictor of term deposit subscriptions. Clients tended to subscribe after longer conversations, suggesting the importance of engaging clients effectively during calls.

Previous attempts at contact also played a role, indicating that repeated contact can be fruitful in convincing clients to subscribe.

📜 Author

Thasmiya Nazar

MSc Statistics with Data Science
