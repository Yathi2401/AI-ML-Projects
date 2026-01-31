# ANN Mobile Price Classifier

This project uses an Artificial Neural Network (ANN) to classify mobile phones into 
high price and low price categories based on different technical features.

The dataset includes mobile specifications such as RAM, battery power, internal memory, 
screen size, camera resolution, and other hardware related attributes.

---

## Aim of the Project

To build and train a simple ANN model that learns the relationship between mobile phone 
features and their price range.

---

## Dataset

- CSV file containing mobile phone features
- Target column: price_range  
  - 0 = Low price  
  - 1 = High price  

---

## Steps Performed

- Loaded the dataset using pandas  
- Separated features (X) and target (y)  
- Split data into training and testing sets (75% / 25%)  
- Applied feature scaling using StandardScaler  
- Built ANN with two hidden layers  
- Trained the model using Adam optimizer  
- Evaluated accuracy and loss  
- Saved trained model weights  

---

## ANN Architecture

Input Layer → 8 Neurons → 4 Neurons → Output Layer (Sigmoid)

---

## Training Details

- Optimizer: Adam  
- Loss Function: Binary Crossentropy  
- Epochs: 200  
- Batch Size: 16  

---

## Results

- Test accuracy around 88% – 91%  
- Training and validation accuracy improved steadily  
- Loss reduced over epochs showing good learning  

---

## Files in This Project

- ANN notebook (.ipynb)
- Dataset CSV file
- Trained weights file (ann.weights.h5)

---

## Conclusion

The ANN model successfully learned patterns from mobile phone features and provided good 
accuracy in predicting the price range. This project helped in understanding data 
preprocessing, ANN model building, training, and evaluation.

---

Created by: Your Name

