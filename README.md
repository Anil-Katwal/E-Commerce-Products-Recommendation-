# AI-Powered Product Recommendation System
An interactive web application that leverages Sentence-BERT embeddings and cosine similarity to recommend products based on user queries. Built with Flask and powered by state-of-the-art NLP models for semantic search and recommendation.
## Demo web app:
<img width="1399" alt="Screenshot 2025-06-19 at 10 41 49 PM" src="https://github.com/user-attachments/assets/16c9330c-8f8f-45a0-b8bd-54674890998c" />

## 🚀 Feature:
Semantic product search: Understands natural language queries and retrieves relevant products.

Pre-trained Sentence-BERT model: Uses the all-MiniLM-L6-v2 model for efficient embedding generation.

Cosine similarity ranking: Finds and ranks products most similar to the user's search query.

Responsive UI: Clean, Bootstrap-based interface displaying product images, brand, category, and similarity scores.

Lightweight & easy to run: Minimal dependencies with simple setup.
## 🛠️ Tech Stack:
Python 3.9+

Flask

pandas

sentence-transformers

scikit-learn

joblib

Bootstrap 5

## 📝 Usage:
Enter a product name, brand, or keyword in the search box.

Submit your query to see the top relevant products ranked by similarity.

Click on product images or titles to learn more (extend functionality as needed).

## ⚠️ Notes:
The product_embeddings.joblib file contains precomputed embeddings and product metadata necessary for fast search.

Ensure your environment has compatible versions of numpy, pandas, and sentence-transformers.

For best performance, use Python 3.9+.

## 📄 License: 
This project is licensed under the MIT License — see the LICENSE file for details.

