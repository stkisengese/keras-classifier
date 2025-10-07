# Keras Classifier for Breast Cancer Diagnosis

This project demonstrates the implementation of a neural network for early breast cancer diagnosis using the Wisconsin Breast Cancer Dataset. It emphasizes best practices in data preprocessing, model training, and optimization using TensorFlow/Keras.

## Features

*   **Neural Network Implementation**: A fully connected neural network built with Keras's `Sequential` API.
*   **Data Preprocessing**: Demonstrates the critical importance of feature scaling using `scikit-learn`'s `StandardScaler` for optimal model performance.
*   **Training and Optimization**: The `keras_training_optimize.ipynb` notebook provides a clear comparison between training a model on scaled vs. unscaled data, showing a significant improvement in accuracy.
*   **Model Evaluation**: The model's performance is evaluated using accuracy and loss metrics, with training history visualized using `matplotlib`.
*   **Jupyter Notebooks**: The project is organized into two main Jupyter notebooks:
    *   `keras_models.ipynb`: Introduces the basics of building Keras models.
    *   `keras_training_optimize.ipynb`: Covers the end-to-end process of training, and optimizing a classifier.

## Setup and Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/stkisengese/keras-classifier.git
    cd keras-classifier
    ```

2.  **Create a virtual environment and install dependencies:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3.  **Run the Jupyter notebooks:**
    ```bash
    jupyter notebook
    ```
    You can then open and run `keras_models.ipynb` and `keras_training_optimize.ipynb` to see the model in action.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
