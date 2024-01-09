# Alzheimer's Disease Classification using CNN

This project focuses on classifying brain MRI images into three categories: Alzheimer's Disease (AD), Cognitive Normal (CN), and Mild Cognitive Impairment (MCI). The Convolutional Neural Network (CNN) architecture is employed for image classification, utilizing the ADNI dataset.

## Dataset
The dataset used in this project is the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset. It includes brain MRI images of individuals categorized into AD, CN, and MCI classes.

## Libraries Used
- **Scikit-Learn:** Utilized for data preprocessing, model evaluation, and metrics calculation.
- **TensorFlow:** The deep learning framework employed for building and training CNN models.
- **Keras:** A high-level neural networks API (compatible with TensorFlow) used for building and defining the CNN architecture.

## Usage

### Installation
1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/alzheimers_disease_classification_cnn.git
   ```

2. Navigate to the project directory:

   ```bash
   cd alzheimers_disease_classification_cnn
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Data Preparation
1. Download the ADNI dataset from [ADNI website](http://adni.loni.usc.edu/).
2. Organize the dataset into appropriate folders (AD, CN, MCI).
3. Update the data paths in the `config.py` file.

Happy coding!
