This project presents a Movie Recommendation System designed using Content-Based Filtering and extended with Deep Learning techniques to deliver personalized movie suggestions. The system is built using the TMDB dataset and leverages features such as genres, tags, and descriptions to recommend relevant content tailored to user preferences.
Developed as a part of the B.Tech in Artificial Intelligence & Data Science curriculum at Chandigarh Engineering College, Jhanjeri (Batch: 2022–2026), this model explores various recommendation strategies and evaluates their performance.

Features:
Personalized recommendations based on user history
Utilizes TF-IDF vectorization and cosine similarity
Compares performance with:
Collaborative Filtering
Matrix Factorization
Neural Collaborative Filtering (NCF)
Evaluation using metrics like Precision, Recall, and F1-score
Visual comparison of different models' performance
Addresses cold-start and data sparsity challenges

Techniques Used:
Content-Based Filtering
Collaborative Filtering
Matrix Factorization (SVD)
Neural Collaborative Filtering (NCF)
Autoencoders
TF-IDF and Cosine Similarity

Results:
Technique	Precision	Recall	F1-Score
Content-Based Filtering	0.78	0.72	0.75
Collaborative Filtering	0.65	0.60	0.62
Matrix Factorization	0.70	0.68	0.69
Deep Learning (NCF)	0.74	0.70	0.72

Content-Based Filtering provided the best performance in the current model setup.

Tech Stack:
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
TensorFlow / Keras
Google Colab
TMDB Dataset

Dataset:
TMDB 5000 Movies Dataset
Contains movie metadata, user ratings, genres, cast, and descriptions.
Preprocessing includes encoding categorical data and cleaning missing values.

Workflow:
Data Collection
Preprocessing & Feature Engineering
Exploratory Data Analysis
Model Building (Content-Based & Deep Learning)
Training & Evaluation
Performance Comparison
Deployment Planning

Future Enhancements:
Hybrid recommendation system combining content-based and collaborative techniques
Incorporate NLP and sentiment analysis from user reviews
Real-time recommendation engine using Flask/Django
Expand to TV shows, web series, and multi-platform recommendations

Authors:
Amish Bhardwaj (2231131)

Jatin (2231152)

Mukul (2231161)

Paras (2231165)

Rohan (2231170)

Guide: Dr. Ashok Kumar, Professor, CEC Jhanjeri

License:
This project is intended for educational and academic purposes under the guidance of Chandigarh Engineering College, Jhanjeri. Use appropriately and cite the source if referenced.
