# Product-recommendation-system
Product Recommendation System is a machine learning project that leverages user interaction data to suggest relevant products using collaborative filtering techniques. This system analyzes purchasing or viewing patterns to build a personalized recommendation engine, functionality seen in major e-commerce platforms like Amazon or Flipkart.


## 📌 Project Objectives

- Analyze product ratings and user engagement
- Rank products using popularity-based heuristics
- Handle missing data and clean product attributes
- Visualize top-rated and high-demand items

 ## Methods Used in Product Recommendation
### 1. Collaborative Filtering (Item-Based)
Approach: Recommends items based on similarity between items.

Technique: Uses a user-item interaction matrix (e.g., ratings or purchases).

Implementation:

Cosine similarity between items

Scikit-learn’s pairwise_distances or cosine_similarity

### 2. Popularity-Based Recommendation
Approach: Recommends the most popular items overall (or in a category).

Use Case: Good for new users (cold start problem).

Implementation:

Count or rank products by frequency of purchase.

### 3. TF-IDF (Text-Based Content Filtering) (Optional)
Approach: If your dataset contains product descriptions, use TF-IDF to recommend similar items based on content.

Implementation:

from sklearn.feature_extraction.text import TfidfVectorizer

## 📊 Dataset

The dataset includes product metadata such as:
- `product_name`
- `discounted_price`, `actual_price`, `discount_percentage`
- `rating`, `rating_count`
- `about_product` (optional for future content-based use)

## 📈 Features & Techniques

- Data Cleaning: Handling missing prices, ratings, and strings
- Feature Engineering: Calculating combined ratings
- Product Ranking: Based on engagement and review scores
- Visualization: Rating distribution, top products, pricing trends

## 🔮 Future Improvements
Add collaborative filtering (user-item matrix)

Deploy using Flask or Streamlit

Integrate with a real e-commerce dataset

Deep Learning model deployment in real world.

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Akash22AD280/Product-recommendation-system.git
   cd Product-recommendation-system
