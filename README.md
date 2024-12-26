# Yelp Restaurant Review Analysis

This project uses text mining and natural language processing techniques to analyze Yelp reviews of restaurants. The primary goals include sentiment analysis, topic modeling, and identifying key customer concerns.

## Project Overview

This analysis is based on a subset of the Yelp dataset and focuses on extracting valuable insights about customer opinions and their impact on restaurants. Key tasks include:
*   Exploratory data analysis to understand the distribution and key attributes of the data.
*   Applying text mining to understand customer reviews.
*   Analyzing sentiments expressed in the reviews using pretrained sentiment libraries.
*   Identifying prominent themes and topics using N-gram analysis and topic modeling.
*   Studying review trends over time.
*   Comparing how different restaurants and locations are perceived in their reviews.

## Key Findings and Insights

*   **Sentiment Distribution**: A clear understanding of the distribution of sentiments(positive, negative and neutral) in the reviews. There are some significant differences in how different locations and restaurants are perceived by people in terms of sentiments.
*  **Key Themes:** Identified common themes or words mentioned in specific types of reviews (both by restaurant and sentiment types), providing valuable insights for each location or restaurant
*  **Trending topics:** Analysis of how specific words, sentiments or themes changed over time.

## Files

*   `pythonproject__dataexploration&preproccessing-9.md`: Contains all of the preprocessing analysis and data exploration
*   `pre processing/`: Folder containing images and visualizations of trends, distributions, and sentiments.

## Technologies Used

*   Python (with libraries like Pandas, NLTK, TextBlob, Scikit-learn)
*   Text Mining Techniques
*   Sentiment Analysis
*   Topic Modeling
*   N-Gram Analysis

## How to Use

1. Download all the files from this repository
2.  Import the dataset into Python using pandas
3. Run the relevant script to produce all the analysis
4. You can explore the EDA images in the `pre processing` folder

## README Extras

### Project Genesis
This project was part of an academic endeavor to study practical applications of text mining and sentiment analysis for business insights, specifically focusing on restaurant reviews.

### Motivation
The project's motivation is driven by the significance of online reviews in influencing consumer choices and the opportunities this presents for businesses to enhance customer satisfaction and refine their strategies.

### Limitations
- Dataset Limitations: The dataset only consists of information on 5 restaurants. The sample size for the project is limited, preventing the possibility of a more generalized analysis.
- Model Limitations: The selected sentiment and topic models may not capture the complexities of language, and may require further tuning and more complex models.
- Subjectivity in labeling: Although we used pre-trained libraries and a combination of manual analysis, the process of labeling sentiment data introduces subjective elements, which may lead to certain biases.
* **Absence of Data Sources:** This project demonstrates our process from a processed dataset; however, the method of gathering this data might be missed by the readers.

### Challenges
* Initial Challenges: The project faced challenges in preprocessing the unstructured data and implementing accurate and relevant sentiment analysis
* Technical Challenges: Identifying, implementing and interpreting various unsupervised models was complex
* Presenting Insights: Extracting and articulating significant, actionable insights from complex text data required significant effort and iterations.

### What Problem This Project Solves
This project contributes to better understanding customer feedback, which helps:
    * Restaurants understand customer sentiments toward their services, pinpointing areas for improvement.
    * Consumers are better informed about restaurants' quality, assisting them in making appropriate choices.

### Intended Use
The intended use of this project is to:
    * Serve as a decision making resource for restaurant managers to refine their current practices and improve future performance.
    * Demonstrate how text mining can be implemented on user reviews to gain actionable insights
