# Osteoarthritis Classification from X-Rays Images using CNNs 
*Notes: Research/Education only - not for clinical use*

## Summary:
Develope a deep learning model to classify the severity of knee osteoarthritis from X-ray images using CNN with modification layers, early stopping, and reducing learning rate, evaluation using classification report & confusion matrix for identify precission, recall, and f1-score

## Problem:
Osteoarthritis diagnosis is heavily reliant on the visual inspection of X-ray images by radiologists to assign a severity grade. This manual process faces several key challenges:
1. Subjectivity: Objectivity is necessary when we talking with medical things
2. Time-Consuming: For manual review it takes time to identify one by one image to classify severity osteoarthritis image especially for high-volume data
3. Resources limitation: straining limited radiologist resources for more complex cases

## Methodology:
1. EDA
2. Preprocessing & Augmentation
3. CNN Modeling (Sequential, plus modification transfer learning)
4. Evaluation

## Skills:
- Programming & Data Manipulation: Python, Pandas, NumPy, OpenCV (cv2)
- Data Visualization: Matplotlib, Seaborn
- Deep Learning Framework: TensorFlow, Keras
- Modeling Techniques: Deep Learning, Convolutional Neural Networks (CNNs)
- Model Training & Evaluation: Data Augmentation (ImageDataGenerator), Regularization (Dropout), Callbacks (EarlyStopping)

## Results:
- The baseline CNN turns out the strongest and more stable performance
- The modified CNN underperformed compared to baseline model which means adding more layers and more complex model didn't make the model perform better

## Next Steps:
- Using Transfer Learning such as efficientNetB0
- Tune Trials Hyperparameters
