Predicting Cocoa Seedling Survival in Ghana using Machine Learning and Early Growth Indicators
Why this project
Ghana is the world's second largest cocoa producer, yet the sector is held back by persistently high seedling mortality after transplanting. As an extension officer at Ghana Cocoa Board (COCOBOD), I worked directly with farmers who raised the same concern again and again: the seedlings they collected from cocoa stations often did not survive in the field.
This project set out to investigate the problem using data, and to test whether seedling survival could be predicted early enough for nurseries and extension officers to act.
The question
Can early growth indicators, measured at the nursery stage, predict which cocoa seedlings will survive after transplanting to the field?
Data
The study used records for 1,000 seedlings from COCOBOD's Akwadum nursery, tracked across four early growth indicators during the nursery phase. The dataset was collected and prepared for analysis as part of my MSc Business Analytics dissertation at the University of Northampton.
Methods
•	Exploratory data analysis and data cleaning in Python (Pandas, NumPy)
•	Class imbalance handled using SMOTE
•	Classification models: Random Forest and Logistic Regression
•	Cross-validation and performance evaluation using accuracy, precision, recall and F1-score
•	Feature importance analysis to identify which early growth indicators carried the most predictive weight
Key findings
•	The nursery itself achieved a 98.6% seedling survival rate, which reframes Ghana's cocoa mortality issue. The problem is not nursery quality, it is field establishment after transplanting.
•	Early growth indicators showed meaningful predictive signal, suggesting that nursery-stage monitoring can flag at-risk seedlings before they reach farmers.
•	Classification accuracy of over 92% was achieved using Random Forest with SMOTE.
Why it matters
If nurseries and extension officers can identify at-risk seedlings before transplanting, interventions can be targeted where they will make a difference, protecting farmer livelihoods and supporting Ghana's cocoa economy. The finding that the nursery is performing well shifts policy attention toward post-transplant support, which is where the real losses are happening.
Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, SMOTE, Jupyter Notebook
Acknowledgements
MSc dissertation supervised by Dr Samsad Reza, University of Northampton. Data access provided through Ghana Cocoa Board (COCOBOD).
Author
Edna Ann Quarshie
MSc Business Analytics (Distinction), University of Northampton
