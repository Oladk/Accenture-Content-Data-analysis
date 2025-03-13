# User Engagement Analysis Project

This repository contains the analysis and insights derived from user engagement data across different content types, categories, reaction types, and time periods. The goal of this project was to understand user preferences and provide actionable recommendations to improve content strategy.

---

## **Project Overview**

### **Objectives**
1. Identify patterns in user engagement across content categories and types.
2. Analyze sentiment and reaction trends over time.
3. Uncover the optimal combinations of content type, category, and timing for maximum positive engagement.
4. Provide actionable insights to improve low-performing content.

---

## **Datasets**

Three datasets were used in this analysis:
1. **Reactions.csv**: Contains user reactions, timestamps, and associated content IDs.
2. **Content.csv**: Provides details about content type and category linked to each content ID.
3. **ReactionTypes.csv**: Maps reaction types to sentiment (positive/negative) and scores.

---

## **Key Columns in the Final Dataset**
- `Content ID`: Unique identifier for the content.
- `Content Type`: The type of content (e.g., video, text).
- `Category`: The category of the content (e.g., Studying, Food).
- `Reaction Type`: The type of user reaction (e.g., dislike, like, disgust).
- `Datetime`: Timestamp of the user reaction.
- `Sentiment`: Sentiment of the reaction (positive/negative).
- `Score`: Numerical score associated with the reaction.

---

## **Methodology**

The analysis followed these steps:
1. **Data Preparation**:
   - Merging datasets on common keys (`Content ID`, `Reaction Type`).
   - Cleaning and transforming data (e.g., converting timestamps to datetime, handling missing values).
   
2. **Exploratory Data Analysis (EDA)**:
   - Identified trends in user reactions by content type, category, and time.
   - Explored the distribution of reaction types and sentiment scores.

3. **Analysis and Insights**:
   - Examined the relationship between content attributes and user engagement.
   - Identified high- and low-performing content types and categories.

4. **Recommendations**:
   - Proposed strategies to improve content alignment with user preferences.

---

## **Key Insights**

1. **Top Performing Content**:
   - Content related to "Animals", "Science" and "Healthy Eating" have the most engagements.
   - However, the "Public Speaking", "Technology" and "Education" categories have the highest positive sentiment rates.

2. **Timing Patterns**:
   - Peak engagement occurred on Monday and Friday, early in the mornings (around 6 AM) and late at night (around 11 PM).
   - Positive reactions rates are highest at 9 pm .
   - Overall, positive sentiments consistently outnumber negative sentiments.

3. **Reaction Trends**:
   - Content in the Public Speaking category shows a higher proportion of Positive sentiments (59.2%), while Cooking content has a significant share of Negative sentiments (32.91%).
   - Photos consistently generate more positive sentiments but in terms of rates, the audio contents have the higher rates.

---

## **Technical Details**

### **Tools and Libraries**
- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for visualizations.
  - `scipy.stats` for statistical analysis.

---

## **Visualizations**

The project includes several visualizations to support the analysis:
- Distribution of reaction types across content categories.
- Distribution of total Engagement by Category
- Sentiment trends over time.
- Engagement patterns by day of the week and time of day.
- High vs Low Scoring Reactions by Hour and Day.

---

## **Key Recommendations**

1. Focus on educational, animals and science content to maintain user engagement.
2. Schedule posts during peak engagement hours (Monday and Friday, early in the mornings and late at night).
3. Experiment with reformatting low-performing content to align with successful patterns.
4. Use data-driven methods to optimize combinations of content type, category, and timing.

---

## **How to Use This Repository**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/user-engagement-analysis.git
