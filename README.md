# SMS Spam Detection

## Project Overview
The proliferation of online platforms has led to an overwhelming volume of unsolicited messages, including promotional and fraudulent content, inundating consumer inboxes. This deluge of spam obscures essential communications, diminishing user experience.

## Project Objective
This project aims to develop a robust SMS spam detection model capable of accurately classifying messages as legitimate or spam. By leveraging Natural Language Processing (NLP) techniques and the Naive Bayes algorithm, we analyze a dataset of 5,574 SMS messages labeled as either "ham" (legitimate) or "spam." This will contribute to the development of effective spam filtering solutions, enhancing user experience and mitigating the negative impacts of unsolicited messages.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Streamlit Deployment](#streamlit-deployment)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/sms-spam-detection.git
cd sms-spam-detection
```
2. Create a virtual environment:
    ```bash
    python -m spam_sms_project_venv
    ```
3. Activate the virtual environment:
    - On Windows:
        ```bash
        spam_sms_project_venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source spam_sms_project_venv/bin/activate
        ```
4. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
# Data
The dataset used for this project is the raw.csv file in the data folder of this repository. It consists of 5,574 SMS messages with corresponding labels indicating whether the message is spam or ham.

# Model

The SMS spam detection model leverages Natural Language Processing (NLP) techniques and the Naive Bayes algorithm. The preprocessing steps include text cleaning, tokenization, and vectorization.

# Evaluation

The model achieved [accuracy, precision, recall, F1-score] on the testing set.

# Streamlit Deployment

To run the Streamlit app, use the following command:
```bash
streamlit run src/streamlit_app.py
```


# License

This project is licensed under the MIT License - See the [LICENSE](LICENSE) file for details.
