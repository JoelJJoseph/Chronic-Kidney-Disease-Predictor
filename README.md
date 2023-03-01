# Chronic-Kidney-Disease-Predictor

![image](https://images.unsplash.com/photo-1559757175-9e351c9a1301?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8S2lkbmV5fGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60)

# Inspiration <img src="https://user-images.githubusercontent.com/72274851/222214323-923a3fe7-56e9-4ba0-abff-162681500702.png" width="60" height="60"> 

Millions of individuals throughout the world suffer from the terrible health condition known as chronic kidney disease. A patient's ability to effectively manage their condition can be greatly enhanced by early disease identification. 
Yet, it can be difficult to diagnose chronic kidney disease since symptoms might not show up until the condition has advanced sufficiently.

We can identify people who are at a high risk of developing chronic kidney disease and take early preventive action by creating predictive models for the condition. To find patterns and risk factors related to chronic kidney disease, machine learning algorithms can be trained on massive datasets of patient health data, including demographics, medical history, and test findings.

# What it does  <img src="https://user-images.githubusercontent.com/72274851/222216353-58874ba5-d9cc-4298-baab-4255bbdb0193.png" width="60" height="60">  
In order to identify patients who are at a high risk of developing chronic kidney disease, the chronic kidney disease prediction project uses machine learning algorithms to create predictive models. Large databases of patient health data, including demographics, medical history, and test findings, are used to train these algorithms. The project's goal is to assist healthcare professionals in taking early action with individualised therapies to either prevent or manage chronic kidney disease by detecting trends and risk factors related to the condition. The project's objective is to enhance patient outcomes and lessen the burden of chronic kidney disease, which will ultimately result in lifesaving and quality-of-life improvements for millions of individuals around the world.

# How i made it <img src="https://user-images.githubusercontent.com/72274851/222215141-6ced575e-414b-4088-bd99-d78921f80f66.png" width="60" height="60"> 

✅ Collect data.

✅ Preprocess data: The data needs to be cleaned, preprocessed, and transformed into a format that can be used by machine learning algorithms.
![image](https://user-images.githubusercontent.com/72274851/222221113-2e8c5b21-88f0-4952-a862-d7579f64eeff.png)

![image](https://user-images.githubusercontent.com/72274851/222221139-bce8df90-08ed-4984-8933-c502df4718f9.png)


✅ Feature engineering: Features need to be selected or engineered from the data that are relevant to predicting chronic kidney disease.

✅Select machine learning algorithm: There are several algorithms that can be used for predictive modeling, including logistic regression, decision trees, random forests, and neural networks. The algorithm selected will depend on the specific requirements and characteristics of the data.

✅ Balanced the dataset ![image](https://user-images.githubusercontent.com/72274851/222211438-2bbab41d-9275-4c6c-9c3b-ec4c182ebe42.png)
![image](https://user-images.githubusercontent.com/72274851/222211493-33f11ebb-25a2-466c-b84e-b95ec801cace.png)

✅ Train and Test the model using intel oneAPI 

![image](https://user-images.githubusercontent.com/72274851/218504609-585bcebe-5101-4477-bdd2-3a1ba13a64a8.png)



✅ The result is as shown

![image](https://user-images.githubusercontent.com/72274851/222221231-a7f6720d-a2e7-4fbc-9393-b21308f91638.png)


## Dependencies <img src="https://user-images.githubusercontent.com/72274851/222215296-64d3a566-02c2-4ff9-9b8f-9ec5096f5799.png" width="60" height="60"> 
This project requires the following dependencies:

✅ Python 3.7 or higher

✅ Scikit-learn

✅ XGBoost

✅ Pandas

✅ NumPy

✅ Matplotlib

✅ Seaborn

# Usage <img src="https://user-images.githubusercontent.com/72274851/222215440-158ffdc1-8a23-4c7f-81c2-44e864d6d043.png" width="60" height="60"> 

To run the project, follow these steps:

- [x] Clone this repository to your local machine.
- [x] Install the dependencies listed above.
- [x] Open a terminal and navigate to the project directory.
- [x] Run the Chronic_Kidney_Disease.ipynb Jupyter notebook to train and evaluate the machine learning model.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Chronic Kidney Disease dataset to build a classification model that can correctly classify either having or not having chronic kidney disease using measured features.
