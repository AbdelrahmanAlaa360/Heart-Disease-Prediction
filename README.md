# Heart Disease Prediction
Heart disease is a major health concern worldwide and can lead to serious health complications and even death. There are several factors associated with heart disease as high blood pressure, cholesterol, smoking, and family history of heart disease. Machine learning can be used to predict the likelihood of heart disease based on various risk factors.

# Used Dataset
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

### Attributes
- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- fasting blood sugar > 120 mg/dl
- resting electrocardiographic results (values 0,1,2)
- maximum heart rate achieved
- exercise induced angina
- oldpeak = ST depression induced by exercise relative to rest
- the slope of the peak exercise ST segment
- number of major vessels (0-3) colored by flourosopy
- thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

# Preprocessing
- [ ] Removing **duplicated** data.
- [ ] Removing **null** values.
- [ ] Separating data into categorical and numerical.
- [ ] Encoding the **categorical values**.
- [ ] Applied **feature scaling** to numerical values to make them all in same range.

# Conclusion
- The K-Nearest Neighbors (KNN) algorithm was chosen to train the model and achieved good performance with an accuracy of **80.32%**
- Finally, the model was saved using the **joblib** library, which allows it to be loaded and used in other applications and tested using **GUI**.
- The project demonstrates how ML algorithms can be used to predict heart disease in patients with good accuracy, which can aid in early detection and treatment of the disease.

### Feature Scaling
![image](https://user-images.githubusercontent.com/71105404/236198588-dcefc980-1d87-456e-b15f-a2cde8acdf3b.png)

### Accuracies with different K values

![image](https://user-images.githubusercontent.com/71105404/236197561-8fe8c7dd-b79f-434c-97b3-38f826a68f7e.png)

### Testing Model Using Simple GUI
![image](https://user-images.githubusercontent.com/71105404/236197430-059b62ec-4951-4ccc-a120-18be17ebf389.png)
