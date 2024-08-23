# Dog Breed Classification Project

This project classifies pet images as dogs or not dogs, and further identifies the breed of the dog. It uses various scripts for preprocessing, classification, and result evaluation.

## Table of Contents

- [Project Overview](#project-overview)
- [Files and Scripts](#files-and-scripts)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project involves a series of steps to classify images of pets. It includes image preprocessing, label extraction, and classification using a pre-trained model. The results are adjusted, and statistics are calculated to evaluate the model's performance.

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

 **Classify images**:
    ```bash
    sh run_models_batch.sh
    ```

## Licensing
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact:

Victor Muthii Munene
- LinkedIn: [Victor Muthii Munene](https://www.linkedin.com/in/victor-muthii/)
- Email: [mv.munene01@gmail.com](mailto:mv.munene01@gmail.com)

---
