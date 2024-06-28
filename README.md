# Projects

### London Air Polution

This project involves the analysis and visualization of air quality data in London over multiple years (2013, 2016, and 2019). The goal was to observe the changes in pollution levels across different boroughs. The data was taken from the GLA and TFL Air Quality

<details>
  <summary>Expand for more detail</summary>
  <p>In this project, I retrieved and stored stock data using yfinance in a SQL database to maintain a robust and scalable data storage solution. The trading strategies implemented include the Moving Average and Triple Exponential Moving Average to generate buy/sell signals in trading.</p>
  <p>The project involved the following key steps:</p>
  <ul>
    <li><strong>Data Preparation:</strong> I downloaded air quality concentration data that inc.</li>
    <li><strong>Data Extraction:</strong> I implemented the Moving Average and Triple Exponential Moving Average strategies to generate buy and sell signals based on the historical data.</li>
    <li><strong>Data Extraction:</strong> Conducted thorough backtesting of the implemented strategies using historical data. This helped in evaluating the performance of each strategy and understanding its strengths and weaknesses.</li>
    <li><strong>Data Extraction:</strong> Integrated visualization tools to plot stock prices, moving averages, and trading signals. This provided a clear visual representation of the strategies and their performance over time, aiding in qualitative analysis.</li>
  </ul>
  <p>The results of the backtesting and visualizations provided insights into the effectiveness of the strategies, helping to refine and improve them further.</p>
</details>

### Stock Trading Strategy Backtesting

Stock Trading Strategy Backtesting is a personal project where I developed and tested various stock trading strategies using historical stock data. The goal was to evaluate the performance of different strategies and visualize the results for analysis.

<details>
  <summary>Expand for more detail</summary>
  <p>In this project, I retrieved and stored stock data using yfinance in a SQL database to maintain a robust and scalable data storage solution. The trading strategies implemented include the Moving Average and Triple Exponential Moving Average to generate buy/sell signals in trading.</p>
  <p>The project involved the following key steps:</p>
  <ul>
    <li><strong>Data Retrieval and Storage:</strong> I fetched historical stock data with yfinance and stored it in a SQL database, ensuring efficient data management and retrieval for backtesting.</li>
    <li><strong>Strategy Implementation:</strong> I implemented the Moving Average and Triple Exponential Moving Average strategies to generate buy and sell signals based on the historical data.</li>
    <li><strong>Backtesting:</strong> Write code to use the buy/sell signals from the strategy to conducted a backtesting using the historical data. This helped in evaluating the performance of each strategy and understanding its strengths and weaknesses.</li>
    <li><strong>Visualization:</strong> Integrated visualization tools to plot stock prices, moving averages, and trading signals. This provided a clear visual representation of the strategies and their performance over time, aiding in qualitative analysis.</li>
  </ul>
</details>

### Stock Diversification Tool

The Stock Diversification Tool is a personal project aimed at  identifying relationships among stocks listed on Nasdaq. Using a dataset of monthly log returns, I constructed a minimum spanning tree (MST) that connects each stock based on their correlation and developed a Python tool to provide stock recommendations based on their location in the MST.

<details>
  <summary>Expand for more detail</summary>
  <p>In this project, I compiled a comprehensive dataset of monthly log returns for all stocks on Nasdaq over a three-year period. This dataset served as the foundation for analyzing stock relationships and making informed diversification recommendations.</p>
  <p>The project involved the following key steps:</p>
  <ul>
    <li><strong>Data Compilation:</strong> Collected and compiled a dataset of monthly log returns for Nasdaq-listed stocks over a three-year period using yfinance. This involved cleaning and preprocessing the data to ensure accuracy and reliability.</li>
    <li><strong>Minimum Spanning Tree Construction:</strong> Utilized the dataset to construct a minimum spanning tree (MST). The MST helped in identifying and visualizing the relationships and correlations among different stocks.</li>
    <li><strong>Python Tool Development:</strong> Developed Python code to interact with the MST. The tool provides stock recommendations by analyzing the distance and position of stocks within the MST.</li>
  </ul>
</details>

### Reddit Investment Discussion Analysis

The Reddit Investment Discussion Analysis is a personal project designed to analyze discussions on investment-related subreddits. By extracting and analyzing data from Reddit, this project aims to identify the popularity and sentiment of various stocks being discussed.

<details>
  <summary>Expand for more detail</summary>
  <p>In this project, I developed a Python script to interface with the Reddit API and extract data from investment-related subreddits. The extracted data includes post titles, post bodies, and comments. The project involved several key steps:</p>
  <ul>
    <li><strong>Data Extraction:</strong> Developed a Python script to connect to the Reddit API and gather data from specific subreddits focused on investments. This included extracting post titles, post bodies, and comments to create a comprehensive dataset.</li>
    <li><strong>Stock Mention Analysis:</strong> Processed the extracted text to identify mentions of stocks. By counting and analyzing these mentions, the project aimed to determine the popularity and frequency of different stocks being discussed on Reddit.</li>
    <li><strong>Sentiment Analysis:</strong> Implemented Natural Language Processing (NLP) techniques to perform sentiment analysis on the extracted text. This helped in discerning the sentiment (positive, negative, or neutral) associated with each stock mentioned in the discussions.</li>
  </ul>
  <p>The resulting analysis provides insights into which stocks are most frequently discussed and how they are perceived by the Reddit investment community.</p>
</details>

### Movie Recommendation

The aim of this group project was to provide movie recommendations based on a user-inputted prompt, such as a brief synopsis of the kind of movie they're interested in. The recommendations were generated using two adjacent methods: one based on plot similarities and the other predicting films the user would enjoy.

<details>
  <summary>Detailed Explanation</summary>
  <p>For this project we developped two models: A vectorizer and a deep-learning model to predictpotential films. Both model worked together with the results being combined into a sinlge list of recommendations. Below are the key components and steps involved in the project:</p>
  <ul>
    <li><strong>Data:</strong> For the vectorizer, we needed a dataset of short movie summaries that can be vectorized and compared to the user prompt. This dataset was custom made using the OpenAI API, where short summaries where made for list of films. For the deep learning model, we used a Kaggle dataset of user movie reviews.</li>
    <li><strong>Model Training:</strong> The vectorizer was fitted and transformed on the processed film summary dataset. The deep learning model was trained to suggest films that users who enjoyed similar films to the prompt also liked.</li>
    <li><strong>Movie Recommendation:</strong> The scores from the vectorizer, given by taking the cosine similarity to the prompt, where combined with the scores from the DL model. This resulted in a single list of recommendations that took into account the simmilarity as well as predicted enjoyment for the prompt. </li>
  </ul>
</details>

### Segmentation of Lung Images using Neural Network

This project aimed to develop a model capable of performing lung segmentation on chest CT scans and creating a 3D model of the lungs. The segmentation model was trained using a Convolutional Neural Network (CNN), achieving an accuracy of 86%.

<details>
  <summary>Detailed Explanation</summary>
  <p>This was my final year university project, where I focused on training a model to accurately identify and segment lungs in chest CT scans, identifying the left and right lungs along with the bronchial-trachea airways. Below are the key components and steps involved in the project:</p>
  <ul>
    <li><strong>Dataset Creation:</strong> To train the model, I created a custom dataset. Using MONAI Label (image labelling tool) and 3D Slicer (medical imaging tool), I semi-manually performed segmentations on a dataset of chest CT scans. This process involved careful annotation and verification to ensure high-quality data for training.</li>
    <li><strong>Model Training:</strong> With a dataset of 40 annotated CT scans, I trained the model using the 3D U-Net architecture. The training process was conducted over 500 epochs, using the MONAI framework for deeplearning in healthcare imaging.</li>
    <li><strong>Model Performance:</strong> The trained model was evaluated on a validation dataset, achieving an accuracy of 86% in lung segmentation. The overall model accuracy was limited by its performance labelling the airways, however its performance on the lungs was closer to 90%.</li>
  </ul>
