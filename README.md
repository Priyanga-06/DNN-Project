# DNN-Project

## Smart Pet Mood & Needs Prediction System (DNN)

# 📌 Project Overview

This project is an AI-based Smart Pet Care System that uses a Deep Neural Network (DNN) to analyze pet behavior described in text form and predict whether the pet is hungry, not hungry, or confused.
Based on the prediction, the system also provides food recommendations, mood improvement tips, and reasons for the pet’s behavior.

This project is designed as a simple but intelligent mini-project, suitable for resumes and academic submissions.

# 🎯 Problem Statement

Pet owners often struggle to understand what their pet needs based on its behavior.
This project helps by:

Interpreting pet behavior text

Predicting hunger or mood state

Suggesting suitable food and care tips

#  Solution Approach

Convert pet behavior text into numerical format using a tokenizer

Train a Deep Neural Network (DNN) on simple labeled data

Predict the pet’s current need

Provide human-understandable recommendations

# Technology Used

Python

TensorFlow & Keras

NumPy

Deep Neural Network (DNN)

🏗️ Model Architecture (DNN)

Embedding Layer (text representation)

Flatten Layer

Dense Layer (32 neurons, ReLU)

Dense Layer (16 neurons, ReLU)

Output Layer (Sigmoid activation)

This architecture qualifies the model as a Deep Neural Network.

📥 Input

The user provides a text description of the pet’s behavior, for example:

my dog is barking and running to the kitchen

📤 Output

# The system predicts:

🐾 Pet hunger status (Hungry / Not Hungry / Unclear)

🍲 Recommended food options

🎯 Mood improvement tips

💡 Reason for the prediction

🖥️ Sample Output
⚠️ Your pet MIGHT BE HUNGRY.
🍲 Recommended Food Options:
   - Soft cooked rice with boiled chicken
   - Dog-friendly dry kibble

🎯 Mood Improvement Tips:
   - Speak softly and stay near the pet
   - Give small snacks first

💡 Reason:
   - Pets show hunger by begging and crying.

🚀 How to Run the Project

Install Python (3.9+ recommended)

Install dependencies:

pip install tensorflow numpy


Run the program:

python pet_needs_classifier.py


Enter pet behavior when prompted

⭐ Key Features

Text-based pet behavior analysis

Deep Neural Network implementation

Food and mood recommendations

Easy to use and understand

Resume-worthy AI mini project

📈 Future Enhancements

Voice input support

Image-based pet emotion detection

Mobile or web application interface

Larger and real-world dataset integration
