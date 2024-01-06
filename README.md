# Read Me

## Introduction

This repository contains code and data related to a study investigating discussions on Reddit regarding the misuse of Ozempic for weight loss and ADHD stimulants for recreational purposes. The central concern of this study is to understand how the purpose of misuse influences sentiments expressed in selected subreddits. The study aims to decipher how the purpose behind drug misuse shapes sentiments in Reddit discussions, focusing on Ozempic and ADHD stimulant misuse.

## Objectives

The objectives of the study include:

1. Scrutinizing sentiments within Ozempic and ADHD stimulant misuse discussions on Reddit.
2. Discerning the impact of the purpose of misuse on sentiments expressed in selected subreddits.

## Data Retrieval

To retrieve the data, the R library "RedditExtractoR" was used (Ivan-Rivera, n.d.). The "find_subreddits" function within this library was employed to identify relevant subreddits where the keywords for this study, Ozempic and ADHD, are commonly found. Ten Ozempic-related and eight ADHD stimulant-related subreddits were selected for analysis.

## Subreddit Selection

The Ozempic-related subreddits include a mix of health-focused and popular culture-focused subreddits, such as r/loseit, r/Health, r/KUWTKsnark, r/pharmacy, r/medicine, r/news, r/Fauxmoi, r/TheBonfire, r/RHOBH, and r/OzempicForWeightLoss.

The ADHD stimulant-related subreddits cover a range of demographics and discussions, including r/adhd_college, r/teenagers, r/adhdwomen, r/ADHD_Life, r/ADHD, r/Vyvanse, r/microdosing, and r/ADHDguide.

## Data Preparation and Preprocessing

Data preprocessing involves several key steps to ensure the text data is suitable for analysis. An inductive approach was employed by converting all text to lowercase, removing punctuation, numbers, and common English stopwords. The resulting clean and standardized text corpus was then used for subsequent text mining analyses.

## Modeling and Analytical Approach

The study employs a combination of sentiment analysis, topic modeling, and word frequency analysis to uncover insights from online discussions about drug misuse. Term Frequency, Term Frequency-Inverse Document Frequency (TF-IDF) Analysis, subgroup comparison, and time series analysis were used to analyze the data.

## Key Variables

Key variables identified from the dataset include shortages, weight loss, misuse, study, Ozempic, and ADHD.

## Code Execution Steps

The code is organized into sections covering data retrieval, subreddit selection, data preparation and preprocessing, modeling, and analytical approaches. Each step is documented with clear explanations and code snippets.

## Data Analysis

The study analyzes the most frequently occurring keywords, distinctive keywords, subgroup comparisons, and temporal trends related to Ozempic misuse for weight loss and ADHD medication misuse. Additionally, adverse effects mentioned in discussions related to Ozempic and ADHD misuse on Reddit are explored using ngrams.

## Conclusion

The study concludes by emphasizing the importance of considering the purpose of drug misuse in shaping online conversations and community dynamics. The findings provide insights into sentiments in discussions related to Ozempic and ADHD stimulant misuse on Reddit, highlighting potential directions for future research in sentiment analysis on social media platforms.

## References

Ivan-Rivera, R. (n.d.). RedditExtractoR: Reddit Data Extraction Toolkit. Retrieved from [https://github.com/ivan-rivera/RedditExtractoR](https://github.com/ivan-rivera/RedditExtractoR)

## License

This code and data are provided under the [MIT License](LICENSE).# glowing-octo-telegram
