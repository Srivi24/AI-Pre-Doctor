# AI Pre-Doctor

**AI Pre-Doctor** is an innovative healthcare project developed as part of the third-year college mini-project under the domain of **Artificial Intelligence (AI)** and **Machine Learning (ML)**. It is designed as an **interactive AI-powered chatbot** that assists users in obtaining healthcare insights and preliminary diagnoses based on their symptoms.

## Project Overview

**AI Pre-Doctor** aims to provide a user-friendly and efficient solution for healthcare diagnosis, making use of machine learning algorithms and a web interface for interaction. The system empowers users to communicate their symptoms through a chatbot, which processes the data, predicts potential health conditions, and provides recommendations.

The project involves multiple stages of AI development, including:

- Data collection and pre-processing
- Model selection (Decision Tree Classifier, Support Vector Machine)
- Model training and evaluation
- Performance analysis using metrics like accuracy, precision, recall, and F1-score

The **Flask** framework powers the web interface, providing a seamless interaction, while **SQLAlchemy** manages database operations with user authentication.

## Features

- **Interactive AI Chatbot**: Users can input their symptoms through a conversational web-based interface.
- **Machine Learning-Based Diagnosis**: The system uses Decision Tree and Support Vector Machine (SVM) models for predictive healthcare diagnoses.
- **Web Interface**: Built with Flask, HTML/CSS, the chatbot is accessible through any web browser, offering a user-friendly interface.
- **Database Management**: Integrated with **SQLAlchemy**, the system supports user authentication and securely stores data.
- **Performance Metrics**: The system evaluates model performance based on key metrics including accuracy, precision, recall, and F1-score.
  
## Technology Stack

- **Programming Language**: Python
- **Frameworks**: 
  - Flask (Web Development)
  - Scikit-learn (Machine Learning)
  - Pandas (Data Handling)
  - SQLAlchemy (Database Management)
- **Frontend**: HTML/CSS (For web interface design)

## System Architecture

1. **User Input**: Users input their symptoms via a web form.
2. **Data Preprocessing**: User data is pre-processed for model consumption.
3. **Machine Learning Models**: Data is fed into pre-trained models (Decision Tree Classifier, SVM) for healthcare prediction.
4. **Response**: Based on the model output, the chatbot returns potential health conditions and recommendations.
5. **Database Integration**: SQLAlchemy is used to manage user data securely, including authentication for data access.

## Project Workflow

1. **Data Collection & Preprocessing**: Cleaned and processed user health data (symptoms and diagnoses) is fed into the machine learning models.
2. **Model Training**: The training dataset is used to build the Decision Tree Classifier and SVM models, with data splitting and cross-validation.
3. **Performance Evaluation**: The system is evaluated based on accuracy, precision, recall, and F1-score to ensure reliable health recommendations.
4. **Web Interface Development**: The front-end user interface is built with Flask and HTML/CSS to simulate a conversation with a healthcare professional.

## Performance Metrics

- **Accuracy**: Measures the correctness of predictions.
- **Precision**: The proportion of true positive results over all positive predictions.
- **Recall**: The ability of the model to identify true positive cases.
- **F1-Score**: Harmonizes precision and recall, providing a balanced evaluation.

## Ethical Considerations

- **User Privacy**: All user data is processed with strict adherence to privacy laws and ethical standards.
- **Data Security**: The system employs encryption techniques to ensure secure data transmission and storage.
- **Transparency**: The system clearly explains how predictions are made, building user trust.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Srivi24/AI-Pre-Doctor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AI-Pre-Doctor
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask app:
   ```bash
   flask run
   ```

## Usage

Once the server is running, access the chatbot via a web browser by visiting `http://localhost:5000`. Input symptoms, and the chatbot will respond with potential diagnoses based on the AI models.

## Future Work

- **Expanded Diagnostic Capabilities**: Integration of more health conditions and symptoms.
- **Advanced User Personalization**: Tailoring predictions and recommendations based on user profiles.
- **Scalability**: Expanding the database and system architecture to handle a larger user base.
- **Multilingual Support**: Adding support for various languages to reach a global audience.

## Contributors

- Srivikas M(Backend Developer, AI/ML Engineer)
- Ratheesh R(Web Developer)
- Naveen K(UI/UX Designer)
- Saravana Kumar G(AI/ML Engineer)

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---
