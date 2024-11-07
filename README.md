# Rock_Paper_Scissors_Image_Classification_using_CNN-TensorFlow-.ipynb
This project uses a CNN in TensorFlow to classify hand gestures for "Rock," "Paper," and "Scissors." Preprocessed images are augmented for robustness, then passed through convolutional and pooling layers to extract features, followed by dense layers. High accuracy proves the model’s effectiveness in gesture recognition.


**Rock, Paper, Scissors Image Classification using CNN (TensorFlow)**

**Overview:**  
This project aims to classify images of hand gestures representing the game "Rock, Paper, Scissors" using a Convolutional Neural Network (CNN) implemented in TensorFlow. The project showcases how CNNs can be trained to effectively recognize and categorize images into distinct classes, highlighting deep learning's potential in computer vision.

**Dataset Preparation:**  
- **Dataset**: Contains labeled images of hands showing gestures for "Rock," "Paper," and "Scissors." Each image is tagged with its corresponding gesture label.
- **Preprocessing**: Images are resized and normalized to improve model training efficiency and accuracy. Data augmentation techniques like rotation, flipping, and scaling are applied to generalize the model and prevent overfitting.

**Model Architecture:**  
1. **Convolutional Layers**: Several convolutional layers with ReLU activation functions capture unique patterns associated with each gesture.
2. **Pooling Layers**: Max pooling layers reduce spatial dimensions, allowing the model to focus on critical features.
3. **Fully Connected Layers**: Dense layers further process the features, culminating in a softmax layer that outputs probabilities for each class (Rock, Paper, or Scissors).

**Training Process:**  
- **Loss Function**: Categorical cross-entropy is used, suitable for multi-class classification.
- **Optimizer**: Adam optimizer with a learning rate adjustment to enhance convergence.
- **Early Stopping**: Monitors validation loss and halts training once performance plateaus, reducing overfitting risks.

**Evaluation and Results:**  
- **Metrics**: Accuracy, precision, recall, and confusion matrix provide insights into model performance across all classes.
- **High Accuracy**: The CNN demonstrates a high accuracy in identifying the correct gesture, proving effective at distinguishing between Rock, Paper, and Scissors.
- **Visualization**: Training and validation accuracy/loss curves indicate the model's learning progress, while confusion matrix visualizations highlight classification precision across each gesture.

**Conclusion:**  
This project illustrates the power of CNNs in image classification tasks. The model's success in identifying Rock, Paper, and Scissors gestures suggests applications in real-time recognition systems, gaming, and human-computer interaction domains, showcasing how CNNs can enhance interactive AI applications.
