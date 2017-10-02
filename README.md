# Emotion Detector

Project that uses OpenCV, Sci-kit Learn, NumPy, TensorFlow and Kivy to implement machine learning and computer vision to detect emotions in faces into Anger, Disgust, Fear, Happiness, Sadness, Surprise, and Neutral.

Problems:
  1. Unable to load Kivy and openCV at the same time. They both trying to access the user's camera led to crashing the program
  2. Small dataset (35,000 images) is not enough to evaluate the emotions accurately
  3. Predict happiness more than other emotions
  
Future Options:
  1. Implement E-detector on mobiles, the smartphone's camera could detect the facial change in users that could be symptoms of disorders.
  2. Song Recommender: Device detects emotion of user and recommend the best songs for him or her.
