# Final Project Submission for Image Classification 

This project is part of the [Machine Learning Path Dicoding](https://www.dicoding.com/learningpaths/30). The goal of this project is to develop an image classification model capable of recognizing different types of waste automatically.

## Project Description

This project utilizes a Deep Learning approach by leveraging the Convolutional Neural Network (CNN) model and the Xception architecture. The main objective is to build a model capable of classifying waste into specific categories.

### Key Features
- **Dataset**: The dataset used can be found at [Kaggle Garbage Classification Dataset](https://www.kaggle.com/datasets/mostafaabla/garbage-classification).
- **Model**: Built using CNN and Xception.
- **Model Formats**:
  - `.h5` (HDF5)
  - `SavedModel` (TensorFlow)
  - `TF-Lite` (for mobile devices)
  - `TFJS` (for web-based applications)
- **Jupyter Notebook**: The project implementation is available on [Kaggle Notebook](https://www.kaggle.com/code/angguncaksono/submission-garbage-classification).

## How to Use

1. **Install Dependencies**
   Ensure you have installed the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. **Download the Dataset**
   Download the dataset from [this link](https://www.kaggle.com/datasets/mostafaabla/garbage-classification) and place it in the appropriate directory.

3. **Train the Model**
   Run the notebook to train the model:
   ```bash
   jupyter notebook
   ```

4. **Export the Model**
   The trained model can be exported into various formats for use on different platforms.

## Directory Structure

- `notebooks/`: Contains Jupyter Notebook files for training and evaluation.
- `models/`: Stores the models in various formats.
- `data/`: Directory where the dataset is stored.

## Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

## Contributing

Contributions are welcome! If you want to contribute, feel free to fork this repository, create a new branch, and submit a pull request.

```bash
git clone https://github.com/alrescha79-cmd/garbage-classification.git
```

```bash
git checkout -b new-feature
```

## Author

This project was created by:
- **[Anggun Caksono](https://www.github.com/alrescha79-cmd)**

If you encounter any issues, feel free to open a [new issue](https://github.com/alrescha79-cmd/garbage-classification/issues).
