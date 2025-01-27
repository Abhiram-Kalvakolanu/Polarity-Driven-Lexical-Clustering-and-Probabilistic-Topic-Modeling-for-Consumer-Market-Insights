# Polarity-Driven Lexical Clustering and Probabilistic Topic Modeling for Consumer Market Insights
<p align="center">
  <img src="https://github.com/user-attachments/assets/a713cac9-675d-439a-800a-d9b21fa87fa3" alt="Project Overview" width="500">
</p>

## Project Overview
This project focuses on analyzing consumer product reviews to uncover actionable insights using Natural Language Processing (NLP). The analysis aims to explore the sentiment dynamics of reviews, identify key topics within positive and negative sentiments, and perform clustering to group reviews based on underlying themes. This provides a deep understanding of consumer preferences and areas for product improvement.

## Dataset
The dataset used in this project was scraped from Amazon earphone product reviews. It includes the following columns:
- **Date**: The date when the review was posted.
- **Number of Stars**: The star rating given by the customer (on a scale of 1 to 5).
- **Target**: Sentiment label indicating whether the review is positive or negative.
- **Text**: The textual content of the customer review.

This dataset provided a rich source of consumer opinions and feedback to conduct a comprehensive NLP analysis.

## Key Objectives
1. **Sentiment Analysis**:
   - Performed sentiment classification to identify positive and negative reviews.
   - Extracted and categorized sentences and words with positive and negative sentiments.

2. **Word and Sentence Collection**:
   - Collected all positive sentiment sentences and words to understand product strengths.
   - Collected all negative sentiment sentences and words to identify potential product drawbacks.

3. **Probability Distribution**:
   - Generated the probability distribution of positive and negative sentiment words to analyze their frequency and significance.

4. **Topic Modeling**:
   - Performed **Latent Dirichlet Allocation (LDA)** to identify key topics from positive and negative reviews.
   - Focused on the most frequently occurring words to reveal customer preferences and product-related attributes.

5. **Clustering**:
   - Utilized **KMeans Clustering** to group text data into clusters based on similar themes.
   - Analyzed the clusters to understand consumer priorities and recurring themes in reviews.

6. **Findings and Insights**:
   - Identified key words like "good," "bass," "quality," and "sound" as highly valued attributes in product reviews.
   - Observed customer trends, such as prioritization of sound quality and product durability over secondary features like packaging.
   - Discovered varying consumer preferences across clusters, highlighting both strengths and areas needing improvement.

## Tools and Techniques
- **Text Vectorization**: Employed `CountVectorizer` for converting text data into numerical format.
- **Sentiment Analysis Libraries**: Used tools to classify and quantify sentiment in reviews.
- **Topic Modeling**: Leveraged LDA for uncovering hidden themes in text data.
- **Clustering Algorithm**: Implemented KMeans to group text data into distinct clusters.

## Conclusion
This project demonstrates the power of NLP in extracting valuable insights from consumer feedback. By combining sentiment analysis, topic modeling, and clustering, the analysis provides businesses with actionable intelligence to refine product offerings and align with consumer expectations.
