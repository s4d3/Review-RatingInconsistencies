# Review-RatingInconsistencies
This repository contains experiments and analyses exploring inconsistencies between user reviews and ratings, particularly using sentiment analysis methods.

# Title
When Reviews Don’t Match Ratings: Exploring Inconsistencies in User Feedback

# Authors
Sari Dewi Budiwati - Suryatiningsih - Pramuko Aji - Rizki Azkia Firmansyah

# Abstract
User reviews and rating scores play a central role in assessing user satisfaction in mobile applications. However, mismatches between textual sentiment and numeric rating scores remain prevalent, especially in informal and multilingual contexts like Indonesian social media. This study investigates review-rating inconsistencies in two Indonesian Quran applications from the Google Play Store. We collected and preprocessed 49,006 user reviews using advanced text normalization techniques, including a newly developed slang dictionary (SlangWordSM) tailored for informal and religious expressions. Reviews were labeled both manually and automatically to assess alignment between text sentiment and rating scores. Feature extraction was conducted using IndoBERT embeddings, followed by classification using eight models including Logistic Regression, SVM, Random Forest, XGBoost, Gradient Boosting, MLPClassifier, DNN, and KNN. Our findings show that up to 30\% of the reviews contain inconsistencies, and that manual labeling captures nuanced sentiment more effectively than automatic methods. Among all classifiers tested, the Deep Neural Network (DNN) model achieved the best performance on the imbalanced dataset, with an accuracy of 88\%, outperforming other models by 1--2 percentage points. Additionally, performance comparison between imbalanced and SMOTE-balanced datasets indicates only marginal differences, suggesting that certain models are inherently robust to label imbalance.

# Publication
Under Consideration in DSE

# Research Grant
This work is part of The Fundamental Research Scheme: NO. 194/PNLT3/PPM/2022. We sincerely express our gratitude to Telkom  University for providing financial support for this research. Additionally, we acknowledge the contributions of all collaborators and researchers involved in this study, whose insights and efforts have been invaluable in achieving these results.

# Author Contribution
Conceptualization, methodology, formal analysis and experiments were performed by [Author 1]; data curation and validation were conducted by [Author 1, 2, 3, 4]; writing-original draft preparation was done by [Author 1], and writing-review and editing were done collaboratively by all authors. All authors have read and agreed to the published version of the manuscript.
