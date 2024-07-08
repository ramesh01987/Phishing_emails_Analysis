# Phishing Emails Analysis
This repository contains a comprehensive analysis of phishing emails, focusing specifically on the [Phishing Email Dataset]

## What are Phishing Emails?
Phishing emails are fraudulent messages designed to deceive recipients into divulging sensitive information such as usernames, passwords, credit card numbers, and other personal details. These emails often masquerade as legitimate communications from reputable organizations or individuals, exploiting trust and prompting the recipient to take actions that compromise their security.

## Dataset

The dataset used for this analysis is obtained from Kaggle and can be found (https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset). It contains a variety of phishing emails that serve as the basis for our study.

## Dataset exploration

In the Dataset Exploration section, I utilized Pandas to perform initial analysis tasks. This included using the head() function to examine basic dataset characteristics and assessing the distribution between two labels: 0 (Non-Phishing) and 1 (Phishing).

## Text preprocessing

Text preprocessing standardizes data and improves email analysis by converting text to lowercase for case insensitivity, removing punctuation to focus on content, and eliminating stop words to reduce noise. Modules used include NLTK, stopwords, and strings

## Top 10 Frequent Words

Using Python modules and techniques, we identify the top 10 most frequent words in phishing and non-phishing emails to uncover distinctive vocabulary.

## Chi-square Test

We use a contingency table and perform a Chi-square test to investigate associations between specific words in email texts and their classification as phishing or non-phishing. This helps determine statistically significant relationships.

## Point Biserial Correlation

Analyzing correlations like the Point Biserial Correlation reveals relationships between variables and email classification, highlighting factors like "money" and "company" with positive correlations, and "enron" and "ect" with negative correlations.

## Email Length Analysis

Mean, median, and standard deviation of email lengths for phishing and non-phishing emails provide insights into email structure and characteristics.

## Paragraph Analysis

Examining the structural aspects of emails complements other analyses and sheds light on organizational patterns.

## Sentiment Analysis

Despite its emotional focus, sentiment analysis reveals valuable insights into the emotional tone and strategies (e.g., urgency, positivity, fear) used in phishing emails.

## Topic Modeling

Using statistical techniques like topic modeling, we aim to uncover abstract topics within the collection of email documents.

## Findings

After analyzing the Phishing Email Dataset, the following insights were discovered:

1. **Correlation with Phishing Classification**:
   - The presence of words like "money" and "company" shows a moderate positive correlation with emails being classified as phishing.

2. **Email Length**:
   - Non-phishing emails tend to have longer average lengths compared to phishing emails.

3. **Paragraph Structure**:
   - Phishing emails typically use shorter paragraphs compared to non-phishing emails, suggesting a different communication style.

4. **Sentiment Analysis**:
   - Non-phishing emails often exhibit a more neutral tone, while phishing emails frequently use emotionally charged language to evoke urgency and fear.

5. **Common Themes in Phishing Emails**:
   - Phishing emails commonly revolve around themes such as urgency and fear, requests for personal information, appeals to trustworthiness, and offers and deals to lure recipients.

6. **Common Themes in Non-Phishing Emails**:
   - Non-phishing emails often focus on internal operations, industry-specific language, and professional or technical jargon relevant to the recipient's sector.








