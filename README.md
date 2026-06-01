# END-TO-END-DATA-SCIENCE-PROJECT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANKET MITHBAVKAR

*INTERN ID*: CTIS8214

*DOMAIN*: DATA SCIENCE

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION ABOUT THIS TASK*:
This task focused on the development of an intelligent disease prediction and healthcare recommendation system that combines machine learning, data preprocessing, and web application development into a single end-to-end solution. The project was implemented using Python in Visual Studio Code (VS Code), which served as the primary development environment for data analysis, model training, backend development, testing, and deployment preparation. The objective of the project was to create a system capable of predicting diseases based on user-provided symptoms and delivering healthcare-related information through an interactive web interface.

The project utilized a healthcare dataset containing disease names and their associated symptoms. Since raw medical datasets often contain redundant features and inconsistent records, the first stage involved extensive data preparation. The dataset was imported using the Pandas library, which enabled efficient manipulation and analysis of structured data. Initial exploration was performed to understand the available symptom attributes and identify unnecessary columns. Several symptom columns ranging from Symptom_7 to Symptom_17 were removed because they were not required for the prediction workflow. This reduction simplified the dataset while preserving the most significant symptom information needed for disease prediction. To improve readability and processing efficiency, the remaining symptom columns were renamed from lengthy attribute names to shorter labels such as s1, s2, s3, s4, s5, and s6. Missing values were then handled by replacing empty entries with “No Symptoms,” ensuring that all records remained complete and suitable for machine learning algorithms. This preprocessing stage enhanced data quality and reduced the likelihood of errors during model training.

The next phase involved transforming categorical data into numerical form using Label Encoding from Scikit-learn. Since machine learning algorithms cannot directly process text-based symptom and disease names, each category was converted into a unique numerical representation. Both disease labels and symptom values were encoded, creating a fully numerical dataset suitable for predictive modeling. This transformation played a critical role in enabling the model to learn meaningful relationships between symptoms and diseases.

After preprocessing, the dataset was divided into input features and target variables. The symptom columns acted as input features, while the disease column served as the prediction target. The dataset was then split into training and testing subsets using the train-test split technique, allowing the model to learn from one portion of the data and be evaluated on unseen records. This approach ensured reliable performance measurement and reduced the risk of overfitting. Several machine learning and data science tools were employed throughout the project, including Pandas, NumPy, Scikit-learn, Pickle, Flask, MySQL, and FuzzyWuzzy. Scikit-learn provided machine learning algorithms and evaluation metrics, while Pickle was used for model serialization. Flask served as the backend web framework, MySQL managed user information and application data, and FuzzyWuzzy enabled intelligent symptom matching for improved user input handling.

The predictive model was developed using the Decision Tree Classifier, which was selected for its ability to handle categorical data effectively and provide interpretable prediction logic. The model was trained using the processed dataset and evaluated using accuracy scores and confusion matrices. Performance analysis demonstrated the model’s capability to identify disease patterns based on symptom combinations. Once training was completed, the model was saved as a serialized file, allowing it to be reused without retraining whenever predictions were required.

A significant aspect of the project was the development of a complete web-based healthcare platform. The Flask application enabled user registration, secure login, profile management, disease prediction, chatbot interaction, and antibiotic recommendation features. User authentication was implemented using bcrypt password hashing to ensure account security. The prediction module accepted symptom inputs from users, converted them into encoded values through fuzzy matching techniques, and passed them to the trained model for disease prediction. The predicted disease was then mapped back to its original medical label and displayed to the user. Several scalable actions were integrated into the system. Automated preprocessing pipelines reduced manual intervention, encoded symptom matching improved user experience, serialized model deployment minimized computational overhead, and database integration supported large-scale user management. The modular architecture also allows future expansion with additional diseases, symptoms, or advanced predictive models.

This project has practical applications in healthcare support systems, symptom-based disease screening platforms, telemedicine services, clinical decision support tools, healthcare chatbots, and digital health applications. By combining data preprocessing, machine learning, web technologies, and intelligent user interaction, the system demonstrates how predictive analytics can assist users in obtaining preliminary health insights quickly and efficiently.

*OUTPUTS*:

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/47cf7255-49ce-4d16-9cdd-a15c6ad526e0" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/1abb806d-edcc-494c-8d68-d641b68d9dd0" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/1a116f7c-f00e-4c0e-ae74-c7bc6191e870" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/46e2e632-ce36-4396-a934-540ff7ffff1e" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/bde5bef9-b89d-4dad-b75f-96e672205131" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/85fc755d-6523-45a6-99b2-2c8145844fdb" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/26c2759b-bb18-473d-99b1-032f5f7e3fe2" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/9db7616b-7d04-47cb-afcf-5c6f04c2c379" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/d1fa5476-f145-413c-ba72-8408d6302355" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/4ee83e92-ad7a-438e-9406-ee3e4d789d17" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/ff60e546-69db-4675-98c3-0d3960a88b13" />

<img width="2557" height="1344" alt="Image" src="https://github.com/user-attachments/assets/990e0e01-6ac7-4183-abd3-d148252f7df1" />

<img width="2557" height="1344" alt="Image" src="https://github.com/user-attachments/assets/703ea6dc-e381-4c09-901b-34b28c23ef09" />

<img width="1336" height="866" alt="Image" src="https://github.com/user-attachments/assets/283361e1-4d15-4b87-8627-c0c6cc5a419e" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/0bfbdd70-4f40-40c6-a80d-d59b1dff9a47" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/ff6c5b51-5711-4761-9097-70d4ba5d6944" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/936039d1-7d5a-42c6-bacb-867e444dd388" />

<img width="2560" height="1344" alt="Image" src="https://github.com/user-attachments/assets/449c89fb-58b6-46dd-8738-4659c15486d8" />

<img width="2557" height="1344" alt="Image" src="https://github.com/user-attachments/assets/d0b0fbec-a4f9-4735-bcf6-7ce0512f0775" />

<img width="2557" height="1344" alt="Image" src="https://github.com/user-attachments/assets/b35d31ce-edc1-4f1c-a6f3-e1b255811a92" />
