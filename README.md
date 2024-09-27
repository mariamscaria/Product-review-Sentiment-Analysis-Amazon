# Product review Sentiment Analysis - Amazon

This script performs sentiment analysis and visualizes the distribution of product ratings from an Amazon review dataset. The analysis is broken down into several steps, each focusing on specific data cleaning, visualization, and sentiment analysis tasks.

First, the script reads the CSV file containing Amazon product reviews and removes rows with null values to ensure data quality. A pie chart is generated to display the distribution of product ratings from the 'Score' column. By using customized colors and a central circle, the chart is transformed into a donut chart, offering a clear and visually appealing representation of the ratings.

The second part of the script applies sentiment analysis to the review text. Using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analyzer from the NLTK library, it calculates sentiment scores—positive, negative, and neutral—for each review. These scores are stored in new columns in the DataFrame. By summing the values of each sentiment category, the script determines the overall sentiment of the dataset, concluding whether the product reviews lean toward being positive, negative, or neutral.
