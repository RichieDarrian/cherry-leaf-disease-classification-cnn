Developed an image classification system to identify five categories of cherry leaf conditions using convolutional neural networks.

Key work:
- Performed exploratory data analysis on image dimensions, aspect ratios, class distributions, and representative samples, identifying significant class imbalance across disease categories.
- Split the dataset into training, validation, and test sets using a 70:15:15 ratio with stratification to preserve class distributions.
- Preprocessed images by resizing them to 224×224 pixels, normalizing pixel values, applying label encoding, and using image augmentation such as horizontal flipping and brightness adjustment.
- Built an AlexNet CNN architecture from scratch as the baseline model and incorporated class weights to address class imbalance.
- Developed a modified model using pretrained DenseNet121 with ImageNet weights and compared its performance against the baseline AlexNet model.
- Evaluated both models using accuracy, precision, recall, F1-score, and confusion matrices, with DenseNet demonstrating stronger and more consistent classification performance.
