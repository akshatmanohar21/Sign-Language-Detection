# Sign-Language-Detection
Libraries used: mediapipe, numpy, scikit-learn, cv2, pickle
It is a Sign language detector. It uses 42 features(marking points) to detect gestures. 
Machine Learning algorithm used: Random Forest Classifier
Steps: 
1. Run collect_imgs.py to collect images for the dataset
2. Run create_dataset.py to create the dataset
3. Run train_classifier.py to train our model. We have used Random Forest Classifier but other models like Gradient Boosting Classifier or SVM can also be used.
4. Run inference_classifier to test our model. 

**For deployment, use Streamlit. Extract a pickle file from train_classifier.py and use github to host your model.

Thank You
