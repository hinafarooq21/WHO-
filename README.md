# Life Expectancy Prediction Project - Group Project

## Project Scope & Motivation

Life expectancy is a critical statistical measure that provides insights into individual and societal health, well-being, and socio-economic status. On an individual level, it influences personal planning, support, and care. On a broader scale, it has significant socio-economic implications, helping governments and organizations understand the needs and risks of populations.

This project aims to leverage data analytics to estimate life expectancies across countries worldwide. The dataset, provided by the World Health Organization (WHO), contains records from 2000 to 2015 across 183 countries. 

## Goals and Objectives

The primary objective of this project is to construct two predictive models to estimate life expectancy:

1. **Minimalistic Model**: Uses the least amount of data necessary to make predictions while maintaining reasonable accuracy. This model is also designed to eliminate bias by focusing on neutral and essential features.
2. **Advanced Model**: Uses a broader range of features, including potentially sensitive data, to achieve better accuracy. The use of sensitive data requires user consent.

### Ethical Considerations

The ethical use of data is a central aspect of this project. Some countries have concerns about sharing sensitive data (e.g., medical records) due to potential financial implications or social repercussions. Our approach ensures:

- Transparency: Users are informed about the type of data being used.
- Consent: The function explicitly prompts for consent before using advanced data.
- Integrity: Features are carefully selected to balance accuracy with ethical considerations.

## Dataset Description

- **Source**: WHO
- **Timeframe**: 2000 to 2015
- **Coverage**: 183 countries (Only 179 countries present in the dataset)
- **Key Characteristics**:
  - Some missing values.
  - Potential inclusion of sensitive population statistics in the advanced model.
