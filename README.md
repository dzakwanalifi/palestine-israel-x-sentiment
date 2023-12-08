# Uncovering Bias: Sentiment Analysis of US Netizens in the Palestine-Israel Conflict on Platform X

## Project Infographics

![Project Infographics](https://github.com/dzakwanalifi/palestine-israel-x-sentiment/blob/681494846cc31c252b2ccae09b32b5c4bee1ab08/Palestine%20Israel%20Sentiment%20Analysis%20Infographics.png)

## Project Overview
"Uncovering Bias" is a comprehensive sentiment analysis project focusing on the opinions and biases of US netizens regarding the Palestine-Israel conflict, particularly on social media platform "Platform X." This project aims to objectively analyze sentiments, identify prevalent emotions, and uncover potential biases in public opinion.

## Motivation
The Palestine-Israel conflict often generates global attention and diverse opinions. Social media platforms are crucial outlets for such discussions, but they also can reflect and perpetuate biases. This project investigates whether these platforms exhibit any biases in user sentiments and discussions about this conflict.

## Methodology
The project implements a multi-faceted approach:

- **Data Collection**: Tweets and posts related to the Palestine-Israel conflict are collected from "Platform X" using `ntscraper`.
- **Preprocessing**: Data cleaning, transformation, and preprocessing are done to structure the dataset for analysis.
- **Sentiment Analysis**: Utilizing tools like VADER and TextBlob, the project analyzes sentiments in the tweets to categorize them into positive, negative, and neutral sentiments.
- **Emotion Analysis**: Using NRCLex, the project identifies dominant emotions in the discussions.
- **Topic Modeling**: LDA is used to uncover prevailing themes and topics in the conversations.
- **Stratified Sampling**: Systematic sampling methods are used to ensure diverse and representative data subsets for analysis.

## Results and Insights
The project provides insights into:
- The shift in sentiment before and after specific events related to the conflict.
- The predominance of specific emotions like fear or anger in discussions.
- The influence of media and external events on public sentiment.
- Identification of major themes and topics discussed in relation to the conflict.

## Tools and Libraries Used
- Python for data processing and analysis.
- Libraries: pandas, numpy, nltk, gensim, matplotlib, and others for various stages of data processing and analysis.

## Repository Structure
- `notebooks/`: Jupyter notebooks containing the analysis and code.
- `data/`: Raw and processed datasets.
- `README.md`: Project overview and repository guide.

## Conclusion
"Uncovering Bias" offers an empirical perspective into how social media sentiment reflects and reacts to the complex dynamics of the Palestine-Israel conflict. This project contributes to understanding how digital platforms can mirror real-world conflicts and biases.

## Authors
- Sachnaz Desta Oktarina, S.Stat., M.Agr., Ph.D. - *Supervisor*
- Muhammad Dzakwan Alifi - *Team Leader*
- Muhammad Rizqa Salas - *Team Member*
- Biki Nurul Afida - *Team Member*
- Indryani Sutisna - *Team Member*
- Naila Dzil Izzati - *Team Member*
