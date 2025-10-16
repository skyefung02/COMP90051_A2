# COMP90051_A2

The following describes what each notebook contains:

* COMP90051_A2_FeatureEngineeringExploration - This notebook contains all exploratory code that was written to explore potential feature engineering options, concerning image augmentation.
* COMP90051_A2_FeatureEngineeringFINAL - This notebook contains code taken from 'COMP90051_A2_FeatureEngineeringExploration', that is used to build the final image augmentation pipeline.
* EDA.ipynb - This notebook contains exploratory data analysis of the training datasets, including data summary statistics, class distribution analysis, color histogram visualization, and image quality assessment for both clean (train_A) and augmented (train_B) datasets.
* randomforest-model.ipynb - This notebook contains the implementation of Random Forest model training with nested cross-validation for hyperparameter tuning, model training and evaluation on both train_A and train_B datasets, outputs test-set predictions
* COMP90051_DEEPCNN - This folder contains all code, saved models and results concerning CNNs. COMP90051_DeepCNN is the notebook that contains the code that was written to perform cross validation, model training, and model predictions on test set, for CNN ONLY.
* model-training-efficientnet-b0.ipynb - This notebook contains the implementation of EfficientNet-B0 model training with nested cross-validation for hyperparameter tuning, model evaluation on both train_A and train_B datasets, and final model training on the complete datasets, as well as testing on the held-out test dataset.
* result-evaluation.ipynb - This notebook contains evaluation of the trained models including bootstrap confidence intervals for performance metrics, and comparative analysis between models trained on clean vs augmented data.





Order of Execution:

1. COMP90051_A2_FeatureEngineeringExploration

2. COMP90051_A2_FeatureEngineeringFINAL

3. EDA.ipynb

4. randomforest-model.ipynb

5. COMP90051_DEEPCNN (folder and notebooks)

6. model-training-efficientnet-b0.ipynb

7. result-evaluation.ipynb
