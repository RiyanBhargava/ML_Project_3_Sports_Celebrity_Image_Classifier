# Sports Celebrities Image Classifier

## Overview
This project is an image classifier that predicts the identity of a sports celebrity using machine learning. The classifier has been trained to distinguish between five well-known athletes: Cristiano Ronaldo, Lionel Messi, Neymar Jr, Novak Djokovic, and Stephen Curry.

## Features
- **Machine Learning Models**: Tested various models including Logistic Regression, SVM, and Random Forest. The Support Vector Machine (SVM) was found to be the best performer.
- **Data Pipeline**: Includes data collection, data cleaning, and feature engineering to ensure high-quality input for the model.
- **Model Deployment**: The trained model is served via a Flask server.
- **Frontend Interface**: Simple and intuitive HTML interface to upload images and display classification results.

## Dataset
The dataset was curated through careful data collection and cleaning to ensure diversity and representativeness of each athlete.

## Model Performance
After testing multiple models, the SVM model was selected based on its superior accuracy and performance.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RiyanBhargava/ML_Project_3_Sports_Celebrity_Image_Classifier.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd ML_Project_3_Sports_Celebrity_Image_Classifier
   ```
3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Flask server:**
   ```bash
   python server.py
   ```
5. **Access the application:**
   Run  ```index.html```

## Usage
- Upload an image of a sports celebrity.
- The model will predict the celebrity's identity and display the result along with a probability score.

## Future Improvements
- Extend the classifier to include more sports celebrities.
- Improve the frontend with additional features and styling.
- Optimize the model further using advanced techniques like deep learning.

## Contributing
Feel free to fork this repository, submit issues, or contribute with pull requests.
