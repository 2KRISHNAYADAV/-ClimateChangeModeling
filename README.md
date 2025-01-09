# Climate Change Modeling

![Screenshot 2025-01-10 003632](https://github.com/user-attachments/assets/4063ffbf-ade8-43f7-b7c0-931a15c359fb)

<div style="background-color: #1e1e2f; color: #d4d4dc; font-family: Arial, sans-serif; padding: 20px; border-radius: 8px;">
  <h1 style="color: #f28b25; text-align: center;">🌍 Sentiment_Climate Insights ML</h1>
  <p style="color: #dcdcaa;">A machine learning project to analyze climate-related sentiments from textual data, leveraging natural language processing (NLP) techniques.</p>

<div style="background-color: #1e1e2f; color: #d4d4dc; font-family: Arial, sans-serif; padding: 20px; border-radius: 8px;">

<h1 style="color: #f28b25; text-align: center;">📊 About the Dataset</h1>


![57d79762ebcd868e5d7000756c1672fb](https://github.com/user-attachments/assets/3e094a75-361b-403a-ab24-9f6211617c3b)

<h2 style="color: #569cd6;">🔍 Overview</h2>
<p style="color: #dcdcaa;">
This dataset encompasses over <strong>500 user comments</strong> collected from high-performing posts on NASA's Facebook page dedicated to climate change (<a href="https://web.facebook.com/NASAClimateChange/" style="color: #569cd6;">NASA Climate Change</a>). The comments, gathered from various posts between <strong>2020 and 2023</strong>, offer a diverse range of public opinions and sentiments about climate change and NASA's related activities.
</p>

<h2 style="color: #569cd6;">💡 Data Science Applications</h2>
<p style="color: #dcdcaa;">Despite not being a large dataset, it provides valuable opportunities for analysis and Natural Language Processing (NLP). Potential applications include:</p>
<ul style="list-style-type: square; color: #9cdcfe;">
  <li><strong>Sentiment Analysis:</strong> Gauge public opinion on climate change and NASA's communication strategies.</li>
  <li><strong>Trend Analysis:</strong> Identify shifts in public sentiment over the specified period.</li>
  <li><strong>Engagement Analysis:</strong> Understand the correlation between the content of a post and user engagement.</li>
  <li><strong>Topic Modeling:</strong> Discover prevalent themes in public discourse about climate change.</li>
</ul>

<h2 style="color: #569cd6;">📜 Column Descriptors</h2>
<ul style="color: #c586c0;">
  <li><strong>Date:</strong> The date and time when the comment was posted.</li>
  <li><strong>LikesCount:</strong> The number of likes each comment received.</li>
  <li><strong>ProfileName:</strong> The anonymized name of the user who posted the comment.</li>
  <li><strong>CommentsCount:</strong> The number of responses each comment received.</li>
  <li><strong>Text:</strong> The actual text content of the comment.</li>
</ul>

  <h2 style="color: #569cd6;">🚀 Features</h2>
  <ul style="list-style-type: square; color: #9cdcfe;">
    <li>Sentiment analysis of climate-related texts (positive, neutral, negative).</li>
    <li>Utilizes cutting-edge NLP models like BERT or GPT for context understanding.</li>
    <li>Data visualization for sentiment distribution and trends over time.</li>
    <li>Pre-trained and fine-tuned models for accuracy.</li>
  </ul>

  <h2 style="color: #569cd6;">🛠️ Technologies Used</h2>
  <ul style="list-style-type: square; color: #9cdcfe;">
    <li><strong style="color: #f28b25;">Programming Language:</strong> Python</li>
    <li><strong style="color: #f28b25;">Frameworks:</strong> TensorFlow, PyTorch</li>
    <li><strong style="color: #f28b25;">Libraries:</strong> Hugging Face Transformers, NLTK, Matplotlib</li>
    <li><strong style="color: #f28b25;">Data:</strong> Climate-related tweets, news articles, and reports</li>
  </ul>





## Overview
This project focuses on analyzing user comments from NASA's climate change Facebook posts. The goal is to extract insights such as comment size distribution and basic statistical summaries using Python libraries for data analysis and visualization.

---

## Code Overview

### Libraries Used
- **pandas**: For data manipulation and analysis.
- **numpy**: To perform numerical operations.
- **plotly**: For interactive data visualization.
- **matplotlib** & **seaborn**: For static visualizations.
- **sklearn**: For machine learning tasks such as preprocessing and modeling.
- **warnings**: To handle warning messages during execution.

---

### Key Functionalities and Explanations

1. **Data Loading and Preview**  
   ```python
   data = pd.read_csv('climate_nasa.csv')
   print(data.head())
   print(data.describe())
