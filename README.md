## Image Classification of Human Facial Expression using Custom CNN Architecture

### **Data Set** :
    1.Images for this data is Scrap from google using `All Images Download` Chrome Extension
    2.Image are Scrap for Happy Faces and Sad Faces

### **Deep Learning Model**:
    1. Train 70% data, 20% Validation data, 10% Test Data
    2. Architecture : 3 CNN Layers with Max pooling and 2 Dense Layer
    3. Optimizer = Adam, Losses= BinaryCrossEntropy, Epochs=20 , Batch Size=20
    4. Data pipeline using tf.keras.utils
    5. Tensorflow version ==2.9.1
