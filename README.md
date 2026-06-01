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
