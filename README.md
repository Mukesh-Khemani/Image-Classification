Image Classification System
This project is an image classification system using a Support Vector Machine (SVM). It includes APIs for predictions, allowing you to easily classify images.

Steps to Use the System
Step 1: Install Dependencies
pip install -r requirements.txt
Step 2: Run Training file
python model/train.py
Step 3: Run The API
uvicorn app.main:app --reload