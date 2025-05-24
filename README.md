# Fake News Detection

A machine learning project for detecting fake news articles using multiple classification algorithms. This repository contains implementations of various models with a focus on achieving high accuracy in distinguishing between real and fake news.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Technologies Used](#technologies-used)  
- [Models Implemented](#models-implemented)  
- [Installation](#installation)   
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
- TfidfVectorizer  (for text to numeric)
- train_test_split
- sklearn.metrics  
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

## Dataset

The dataset contains labeled news articles categorized as *real* or *fake*.  
(Include dataset source here, for example:  
- dataset includes to my repository
- it is a balanced dataset

---

## Contributing

Contributions are welcome! If you'd like to improve this project, please feel free to:  
- Open an issue to discuss your ideas or report bugs  
- Submit a pull request with improvements or bug fixes  

Please follow standard GitHub flow for contributing.

---

## License

This project is licensed under the (mkador).  
---

## Contact

Created by [Md. Musa Kalimulla] – feel free to reach out via [mkador169@gmail.com] for any questions or suggestions.



## Results

| Model                       | Accuracy (%) |
|-----------------------------|--------------|
| Naive Bayes                 | 82.32%        |
| Logistic Regression         | 92.26%        |
| LinearSVC                   | **94.94 %**    |
| Passive Aggressive Classifier | **94.95 %** |

*LinearSVC and Passive Aggressive Classifier achieved the highest accuracy.*

