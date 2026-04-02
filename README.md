# 📚 Book Recommendation System

This project is a simple book recommendation system built using machine learning. The main idea is to suggest similar books to users based on their interests and previous ratings.

## 🔍 About the Project

In this project, I worked with a real-world dataset containing information about books, users, and their ratings. After cleaning and processing the data, I used a KNN-based approach to find similar books.
The system takes a book as input and recommends other books that have similar user rating patterns.

## ⚙️ How It Works
Collected data from three files: books, users, and ratings
Cleaned the dataset by removing duplicates and invalid entries
Filtered active users (users with more than 200 ratings)
Selected popular books (books with at least 50 ratings)
Created a user-item matrix using a pivot table
Converted the matrix into a sparse format for better performance
Applied KNN algorithm to find similar books

## 💻 Tech Stack
Python
Pandas & NumPy
Scikit-learn
Streamlit

## 🚀 Features
Select a book from the dropdown
Get top similar book recommendations
Displays book titles along with their posters
Simple and clean UI using Streamlit

## 📁 Project Structure
book-recommendation-system/
│
├── app.py
├── pickels/
│   ├── model.pkl
│   ├── book_name.pkl
│   ├── final_rating.pkl
│   ├── book_pivot.pkl
│
├── requirements.txt
└── README.md

## ▶️ How to Run
Clone the repository
Install the required libraries
pip install -r requirements.txt
Run the Streamlit app
streamlit run app.py

## 📌 Final Note
This project helped me understand how recommendation systems work in real-world scenarios, especially how user behavior can be used to suggest relevant items.
