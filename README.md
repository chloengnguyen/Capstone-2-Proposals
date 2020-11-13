# Capstone Proposals 
## Proposal 1 - Detecting tumors in thryoid diseases.

### **Overview** 
* The thyroid gland is a butterfly-shaped organ located in the front of the throat that produces and secretes thyroid hormones. It regulates the body's metabolic rate and many other body functions. 

* 60% of people with thyroid diseases are undiagnosed. Women are 8 times more likely to have thyroid issues than men.  

* Thyroid disorders can lead to the development of tumors, which can be benign (non-canerous) or maglignant (cancerous). 

* The object of this study is to build a random forest model that predicts the likelihood a patient would develop a tumor based on the following features: patient's demographics, thyroid medications, surgical history, and the levels of thyroid hormones obtained from blood tests, such as  TSH, T3, T4, TT4, T4U, FTI (Free T4 Index), TBG, etc. 

### **Why?**

For patients with thyroid disorders, a blood test is typically done first to diagnose with a an ultrasound performed after to check for tumors. The ultrasound is often performed automatically, even without other indication that a tumor may be present. Since ultrasounds can be costly in some countries, medically underserved areas, or to uninsured patients, this study aims to assist in determining if the results of the blood test can be used to determine if a patient is at enough risk than an ultrasound would be useful.

### **Concerns** 

There seems to be signficantly more tumor-negative cases than tumor-positive cases in the dataset (for hypothyroidism, there are 40 positive cases out of 3156 cases). This could potentially impact the effectiveness of my model.


### **Source:**
 https://archive.ics.uci.edu/ml/machine-learning-databases/thyroid-disease/


 ---



## Proposal 2 - Thyroid Disease Classifiers

* The blood tests in the dataset are used to diagnose different thyroid issues. A disease is defined by a collection of abnormal values, and different collections of abnormal values corespond to different diseases. Would it be possible to use this data to build a classifier for each thyroid disease using K Nearest Neighbor/ Logistic Regression?  

### **Why?**
It is becoming increasingly popular for physicians to use software that employs algorithms to suggest possible diagnoses based on patient data and lab results. Thyroid diseases are a complex cluster of diseases that rely heavily on multiple pieces of numerical data and so are a good candidate for this method.
