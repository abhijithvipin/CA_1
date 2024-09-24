Data Generation: Generates a DataFrame with synthetic traffic data:

Intersection_ID: Unique identifier for intersections.
Time: A sequence of hourly timestamps.
Traffic_Density: Randomly generated traffic density values (0 to 1).
Light_Timing: Randomly assigned traffic light statuses (Green, Yellow, Red).
Vehicle_Count: Randomly generated counts of vehicles (0 to 100).
Preprocessing:

Encodes the Light_Timing column using LabelEncoder.
Defines features (X) and target variable (y).
Model Training and Evaluation:

Splits the dataset into training and testing sets.
Trains three different models: Logistic Regression, K-Neighbors Classifier, and Random Forest Classifier.
Evaluates each model and prints accuracy and classification reports.
Best Model Identification:

Identifies and displays the model with the highest accuracy

Features
Dummy Data Generation: Creates synthetic data representing traffic conditions at various intersections.
Preprocessing: Encodes categorical variables and prepares the dataset for modeling.
Model Training: Trains multiple machine learning models, including Logistic Regression, K-Neighbors Classifier, and Random Forest Classifier.
Model Evaluation: Evaluates model performance using accuracy and classification reports.

