# Brain Tumor Detection with Deep Learning

![image](https://github.com/Khushalgogia/Brain_tumor_detection/assets/43295537/ffd16eef-7bb4-4a23-90fb-818df02f14af)


In the world of medical diagnostics, the ability to detect diseases accurately and swiftly is paramount. This data science project explores the use of deep learning to detect brain tumors from medical images. With a dataset of 253 brain images, consisting of 155 cases with brain tumors and 98 cases without, we aimed to build a predictive model using the powerful VGG16 architecture. This README takes you through the journey of this project, from data preprocessing to model training and evaluation.

## Dataset

### Gathering and Preparing the Data

The dataset used in this project was a collection of brain MRI images. It consisted of 253 images, with 155 cases of brain tumors and 98 healthy brain images. The dataset was carefully curated and labeled, making it an ideal starting point for the brain tumor detection task.

## Data Preprocessing

Before feeding the images into the model, several preprocessing steps were performed:

- **Image Resizing**: All images were resized to a uniform size (e.g., 224×224 pixels) to ensure consistency for model training.
- **Normalization**: Image pixel values were scaled to the range [0, 1] to facilitate convergence during training.
- **Data Augmentation**: Data augmentation techniques such as rotation, flipping, and zooming were applied to create additional training samples.

## Building the Model

For this project, we chose to implement the VGG16 model, a deep convolutional neural network architecture known for its effectiveness in image classification tasks. VGG16 consists of multiple convolutional and max-pooling layers followed by fully connected layers.

## Training and Evaluation

With the model architecture in place, it was time to train and evaluate its performance. The dataset was split into training and testing sets to assess the model’s ability to generalize to unseen data.

### Model Training

The model was trained using the training set with binary cross-entropy loss and the Adam optimizer. Training was carried out for a specified number of epochs, monitoring both training and validation accuracy.

### Model Evaluation

The trained model’s performance was evaluated using the testing set. Key evaluation metrics included accuracy, precision, recall, and F1-score. These metrics provided insights into the model’s ability to correctly classify brain tumor images.

## Results

After training and evaluation, the model achieved an accuracy of approximately 82%. This meant that the model correctly classified brain tumor images 82% of the time. Furthermore, the model’s precision, recall, and F1-score indicated a good balance between true positives and false positives.

## Conclusion

In this data science project, we leveraged deep learning and the VGG16 architecture to detect brain tumors from medical images. With careful data preprocessing, model building, and evaluation, we achieved an accuracy of 82%, showcasing the potential of deep learning in medical diagnostics.

## Getting Started

To run the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the main script using `python main.py`.

## Contributing

If you would like to contribute to this project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or feedback, please reach out to khushal.gogia122@gmail.com
While this project is a promising step forward, there is still room for improvement. Future work could involve fine-tuning hyperparameters, exploring different neural network architectures, and expanding the dataset to enhance model performance and robustness.

Brain tumor detection using deep learning holds immense promise for early diagnosis and improved patient outcomes, and this project serves as a testament to the power of data science in healthcare.

Thank you for joining us on this journey into the world of brain tumor detection with deep learning. Stay tuned for more exciting data science adventures!
