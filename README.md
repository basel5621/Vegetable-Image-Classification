### Vegetable Image Classification using CNN
This project utilises a convolutional neural network (CNN) for classifying images of vegetables. The dataset used is sourced from Kaggle, particularly the [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset), which contains various images for training, validation, and testing purposes.

##### Features
- Employs the Keras library to build a CNN.
- Incorporates data augmentation techniques like image rotation, zooming, and horizontal flipping to enhance model generalisation.
- Performance of the model is assessed using accuracy metrics, with results visualised through confusion matrices and classification reports.

---

### Vegetable Image Classification using Transfer Learning
This project extends the CNN approach by employing transfer learning using the MobileNet architecture, which utilises the same dataset from Kaggle. Transfer learning facilitates faster model training and potentially higher accuracy by utilising features learnt from a previously trained model.

##### Features
- Adopts MobileNet, pre-trained on ImageNet, for feature extraction.
- The base model's layers are frozen to keep weights intact during the initial phase of training.
- Fine-tunes several fully connected layers atop the MobileNet structure to adapt to the vegetable classification task.

---
### Requirements
- Python 3.x
- TensorFlow 2.x
- Keras
- Matplotlib, NumPy, Pandas

---

### About the Dataset
When utilising this dataset, the following source must be cited:
- [DCNN-Based Vegetable Image Classification Using Transfer Learning: A Comparative Study](https://www.researchgate.net/publication/352846889_DCNN-Based_Vegetable_Image_Classification_Using_Transfer_Learning_A_Comparative_Study)
