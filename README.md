# Dog Breed Classification Project

In this project, I utilized a pretrained classifier developed by Jennifer S., which was trained on 1000 images to identify dog breeds. My role involved writing Python scripts that classified 40 pet images as either dogs or not dogs, and further identified the breed of the dog. I implemented and evaluated the performances of three prominent neural network architectures—AlexNet, VGG, and ResNet—calculating and printing the classification results for each model.

## Table of Contents

- [Project Overview](#project-overview)
- [Files and Scripts](#files-and-scripts)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project focuses on classifying pet images through a series of steps, including image preprocessing, label extraction, and classification using a pretrained model. The classification involves evaluating multiple neural network architectures (AlexNet, VGG, ResNet). After classification, the results are refined, and key performance statistics are calculated to assess the accuracy and effectiveness of each model.

## Files and Scripts

- **pet_images/**: Contains the pet image files used for classification.
- **adjust_results4_isadog.py**: Adjusts the results to differentiate between dog breeds.
- **calculates_results_stats.py**: Calculates statistics from the classification results.
- **check_images.py**: Checks the images for preprocessing.
- **check_images.txt**: Contains information for checking images.
- **classifier.py**: Contains the classifier code.
- **classify_images.py**: Script for classifying images.
- **dognames.txt**: Contains a list of dog names.
- **get_input_args.py**: Handles input arguments for scripts.
- **get_pet_labels.py**: Extracts labels from pet images.
- **imagenet1000_clsid_to_human.txt**: Contains 1000 images used to train the classifier.
- **print_functions_for_lab_checks.py**: Script for lab checks.
- **print_results.py**: Prints the classification results.
- **run_models_batch.sh**: Shell script to run different classifier models on pet images.
- **test_classifier.py**: Tests the pre-trained classifier.

## Installation

To set up and run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/muthii-10/dog-breed-classification.git
    cd dog-breed-classification
    ```
2. **Install Requirements**:
   ```
   pip install -r requirements.txt
   ```
    
## Usage

 **Classify images and Print Results**:
    ```bash
    sh run_models_batch.sh
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact:

Victor Muthii Munene
- LinkedIn: [Victor Muthii Munene](https://www.linkedin.com/in/victor-muthii/)
- Email: [mv.munene01@gmail.com](mailto:mv.munene01@gmail.com)

---
