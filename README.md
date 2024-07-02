# Risk-of-fire-prediction
# Fire Risk Prediction in Morocco

This project focuses on developing a predictive model for fire risk in Morocco using a dataset sourced from Kaggle. The project involves a comprehensive approach to hyperparameter tuning, model recreation, and training using both TensorFlow and PyTorch.

## Project Overview

The main steps of the project include:

1. **Hyperparameter Tuning with TensorFlow**:
    - We defined a range of hyperparameters.
    - Generated all possible combinations.
    - Trained a series of models to identify the optimal configuration.
    - Ensured the model was well-tuned to achieve the best performance on the validation set.

2. **Model Recreation and Training with TensorFlow**:
    - Recreated the model architecture using the best hyperparameters.
    - Compiled it with the appropriate loss function and metrics.
    - Loaded the best weights.
    - Validated the effectiveness of the hyperparameter tuning process, providing a robust model for evaluation.

3. **Model Recreation and Training with PyTorch**:
    - Translated the best configuration from TensorFlow to PyTorch.
    - Leveraged PyTorch's flexibility and efficiency for model training.
    - Converted data to PyTorch tensors.
    - Defined a custom neural network class to match the best configuration.
    - Included batching, regular evaluation, and saving the best model based on validation accuracy.

4. **Final Evaluation**:
    - Thoroughly evaluated the final model's performance using both TensorFlow and PyTorch frameworks.
    - Metrics considered included accuracy, AUC-PR, precision, and recall.
    - Ensured a holistic understanding of the model's capabilities.

## Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/). It contains various features related to fire risk in Morocco.
link : <https://www.kaggle.com/datasets/ayoubjadouli/morocco-wildfire-predictions-2010-2022-ml-dataset>

## Model Performance

The project's key steps ensured a robust and well-optimized neural network model. The comprehensive evaluation was crucial to ensure the reliability of the predictions given the potential impact on fire risk management.

## Tools and Libraries

- **Python**
- **TensorFlow**
- **PyTorch**
- **Pandas**
- **NumPy**
- **Scikit-learn**



## Conclusion

This project demonstrates a structured and methodical approach to machine learning model development, from hyperparameter tuning to model training and evaluation using multiple frameworks. By integrating TensorFlow and PyTorch, we leveraged the strengths of both platforms, resulting in a robust and well-optimized neural network model. The application to fire risk prediction in Morocco underscores the practical significance of the model, which can potentially aid in better preparedness and response to fire incidents in the region.

## Acknowledgements

We would like to thank Kaggle for providing the dataset and the open-source community for their contributions to the tools and libraries used in this project.



