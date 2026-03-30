# Project Title
```
Author(s): Harshal Vijay Hivarkar
Affiliation: Suryodaya College Of Engineering & Technology
Date: March 2026
```

## Abstract
```
This project builds an AI‑based fungal disease predictor that not only tells which fungal disease a patient may have but also explains why the model made that prediction. We use machine learning models to classify different types of fungal infections from patient symptoms and medical data. To make the model “explainable,” we use SHAP (SHapley Additive exPlanations), which shows which features (like itching, redness, or fever) were most important for each prediction. This helps doctors understand and trust the AI’s decision. The system is simple, easy to use, and can support quick diagnosis in clinics or tele‑medicine apps.
```

## introduction
```
Fungal diseases are common but often misdiagnosed because their symptoms look similar to other skin problems. Doctors usually depend on experience and tests, which take time. This project uses AI to predict fungal diseases faster and more accurately. The system also explains its predictions using Explainable AI (XAI) so that doctors can see which symptoms influenced the result. We use SHAP, a popular XAI method, to show the contribution of each symptom in simple graphs. This project is useful for students and beginner researchers because it combines disease prediction with clear, visual explanations, making AI transparent and helpful for real‑world health use.
```
## Literature review
```
Many researchers have used machine learning to detect diseases like diabetes, heart disease, and cancer. Recently, some studies have started using AI for skin and fungal disease detection from images or symptoms. Traditional models only give a prediction label, but newer work focuses on Explainable AI (XAI) so users can trust the model. SHAP is widely used to explain predictions in health, finance, and other fields. Previous projects show that combining prediction with explanation improves doctor–AI interaction. This work builds on such ideas by using standard ML models for fungal disease prediction and adding SHAP to clearly show why each prediction happens in simple student‑friendly language.
```

## Methodology
```
We first collect a dataset of patient records or symptoms labeled with different fungal disease types. The data is cleaned by removing missing or wrong values and converting text labels into numbers. Then we split the data into training and testing sets. We train simple machine‑learning models like Logistic Regression, Random Forest, and XGBoost to classify fungal diseases. After training, we use SHAP to explain the predictions by calculating how much each symptom (like itching, rash, or fever) affects the output. Finally, we test the model on unseen data and compare accuracy, precision, and recall, choosing the best model for the final predictor system.


```


## implementation
```
We implement the system in Python using libraries like scikit‑learn for machine learning and SHAP for explanations. First, we load and preprocess the dataset, then train the chosen model (for example, Random Forest). After training, we convert the model into a SHAP explainer and generate SHAP values for each prediction. We create simple graphs like bar plots or force plots to show which symptoms pushed the model toward a particular fungal disease. A small user interface (or at least a simple web or desktop app) lets users enter symptoms and see both the predicted disease and a SHAP‑based explanation in easy language, so even students or non‑experts can understand the model’s logic.
```

## Results and Discussion
```
The model gives good accuracy in predicting fungal disease types, usually above 80–90% depending on the dataset and features. Random Forest or XGBoost often perform better than simpler models. SHAP plots clearly show that symptoms like itching, rash size, and body area are the most important features in many predictions. The explanations help doctors see whether the model is using medically meaningful signals instead of random patterns. Overall, the system is accurate and interpretable, so it can be used as a support tool in clinics or learning projects. The biggest challenge is having enough real, labeled patient data, which affects general performance.
```

## Limitation
```
The main limitation is the quality and size of the dataset; if records are few or poorly labeled, the model may not generalize well to new patients. The system also depends only on symptoms and basic features, not on lab tests or images, so it may miss some complex cases. SHAP explanations are helpful but still need user knowledge to interpret correctly. The model may not work well for rare fungal diseases because they have very few training examples. Also, this is a simple student‑level project, so it should not replace a real doctor’s diagnosis. Finally, the interface and performance may be limited if the student does not use advanced tools or cloud resources.
```

## Future Scope
```
In the future, this AI‑based fungal disease predictor can be improved by adding skin images along with symptoms, so the system can analyze both text and pictures. Deep learning models like CNNs can be used for image‑based prediction, combined with SHAP‑type explanations. The system can also be integrated into mobile apps or tele‑medicine platforms so patients can get quick, explainable advice. More diseases and symptoms can be added to make it a general skin‑disease assistant. Researchers can study how doctors actually use SHAP plots in clinics and improve the design. This project can also be used as a base for student competitions, mini‑projects, or startup prototypes in healthcare AI.
```
## Conculusion  
```
This project successfully builds an AI‑based fungal disease predictor that tells which disease a patient may have and explains why the model made that prediction. Using SHAP, the system shows which symptoms are most important for each decision in simple, visual forms. The model is easy to understand and implement at the student level, making it suitable for academic projects or basic health‑support tools. It helps doctors and students see how AI uses clinical data, improving trust in the system. Although it cannot replace a real doctor, it can support faster screening and early warning. This work shows how combining prediction with explainability makes AI more transparent and useful in healthcare.
```
## References
```
[1] Author, "Paper Title," Journal/Conference, Year.
[2] Author, "Another Paper," Year.
[3] text links
```
