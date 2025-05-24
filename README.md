# Fake News Detection

A machine learning project for detecting fake news articles using multiple classification algorithms. This repository contains implementations of various models with a focus on achieving high accuracy in distinguishing between real and fake news.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Technologies Used](#technologies-used)  
- [Models Implemented](#models-implemented)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [Dataset](#dataset)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)  

---

## Project Overview

Fake news has emerged as a critical issue impacting public opinion and trust. This project aims to develop an effective fake news detection system by leveraging machine learning classifiers trained on labeled news datasets.

---

## Technologies Used

- Python 3.x  
- scikit-learn  
- pandas  
- numpy  
- nltk / spaCy (for text preprocessing)  
- pickle (for model serialization)  

---

## Models Implemented

- **Naive Bayes**  
- **Linear Support Vector Classifier (LinearSVC)**  
- **Passive Aggressive Classifier**  
- **Logistic Regression**  

Among these, the **Passive Aggressive Classifier** and **LinearSVC** demonstrated the best performance in classification accuracy and were selected for the final model.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mkador/fake-news-detection.git
   cd fake-news-detection




## Results

| Model                       | Accuracy (%) |
|-----------------------------|--------------|
| Naive Bayes                 | 82.32%        |
| Logistic Regression         | 92.26%        |
| LinearSVC                   | **94.94**    |
| Passive Aggressive Classifier | **94.95** |

*LinearSVC and Passive Aggressive Classifier achieved the highest accuracy.*

