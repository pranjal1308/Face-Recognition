# Face-Recognition
Facial Recognition with CNN

This project explores facial recognition using Convolutional Neural Networks (CNNs), a cutting-edge approach in image classification due to CNNs' ability to extract and recognize features at various scales and resolutions. Leveraging Keras, a deep learning library, a CNN was built and trained on the "Labeled Faces in the Wild" (LFW) dataset to assess the effectiveness of CNNs in identifying individuals.

The LFW dataset contains over 13,000 images of faces collected from the Web. For this project, a subset of images corresponding to five individuals, each represented by at least 100 images, was selected. This constraint enables the CNN to train on consistent and varied representations of each individual, enhancing the model's accuracy in facial recognition.

Images were preprocessed to 128x128 pixel color formats to align with CNN requirements, specifically enabling compatibility with pretrained models like ResNet-50. The CNN model was then evaluated on its ability to classify and recognize faces, highlighting the power of CNNs in facial recognition tasks.
