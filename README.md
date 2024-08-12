# Rumor Detection Model on Twitter

## Overview:
This project aims to build a machine learning model capable of detecting rumors on Twitter. The model was developed using Python, and the Random Forest algorithm was selected for its balance between accuracy and interpretability.

---------------------------------
## Steps Involved:
### 1. Data Collection:
- The dataset was gathered from various Twitter sources, including both rumor and non-rumor tweets.

### 2. Data Preprocessing:
- I independently handled data preprocessing to ensure the dataset was clean and suitable for training. This involved:
Handling missing data.
  - Removing duplicates and irrelevant information.
  - Tokenizing and normalizing the text data.
  - Removing stop words and applying stemming/lemmatization.

### 3. Feature Engineering:
- Key features were extracted to capture the linguistic and contextual nuances of the tweets.
These features were then stored in a CSV file, making them readily accessible for model training.
### 4. Model Training:
- A Random Forest classifier was trained on the processed dataset.
Hyperparameters were tuned to optimize performance.
### 5.Model Performance:

- The model's performance was evaluated using standard metrics:
- Accuracy: 0.9362
