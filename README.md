# Airbnb Sentiment Analysis

## Repository Overview

This repository contains the project files for the Airbnb Sentiment Analysis, which explores user reviews from Airbnb listings to extract insights into customer sentiment, trends, and diversity and inclusion related language.

### Repository Structure

-   **`data/`**: Contains the dataset used for the analysis.
    -   `Austin_Reviews.csv`: The dataset containing reviews for Airbnb listings in Austin.
-   **`scripts/`**: Includes the R Markdown file with all the analysis scripts.
    -   `Airbnb_Analysis.Rmd`: The primary script used for data preparation, analysis, and visualization.
-   **`output/`**: Contains the rendered output of the analysis.
    -   `Airbnb_Analysis_Output.pdf`: A detailed PDF report summarizing the project's methodology, results, and visualizations.
-   **`presentation/`**: Houses the presentation slides for communicating findings.
    -   `Airbnb_Analysis_Presentation.pdf`: A slide deck summarizing the main insights.

------------------------------------------------------------------------

## Project Details

### Objective

The goal of this project is to analyze Airbnb reviews to:
- Understand customer sentiment trends over time
- Identify frequently used keywords and phrases
- Conduct sentiment analysis using the Bing and NRC lexicons
- Investigate the use of diversity and inclusion related language in reviews

### Methodology

1.  **Data Preparation**:
    -   Loaded and cleaned data using R libraries such as `readr`, `dplyr`, and `tidytext`.
    -   Handled missing values and extracted key features like review length and date information.
2.  **Sentiment Analysis**:
    -   Leveraged the Bing and NRC lexicons to identify positive, negative, and emotional words in reviews.
    -   Analyzed the sentiment difference over time and explored top words associated with different emotions.
3.  **Diversity Analysis**:
    -   Searched for keywords related to diversity, inclusion, and accessibility.
    -   Analyzed trends in diversity-related language over time and performed sentiment scoring on these keywords.
4.  **Visualization**:
    -   Created comprehensive visualizations to display trends in review sentiment, diversity language mentions, and emotional associations.

------------------------------------------------------------------------

## Results Highlights

-   **Sentiment Trends**: The analysis revealed a general increase in positive sentiment over time, with peaks between 2022 and 2024.
-   **Common Words**: Keywords like "stay," "location," and "clean" were frequently mentioned, reflecting customers’ preferences for cleanliness and convenience.
-   **Diversity Analysis**: Notable mentions of keywords such as "justice," "race," and "accessibility" were observed, with an increase in such language after 2020.

------------------------------------------------------------------------

## Usage

1.  Clone the repository:

    ``` bash
    git clone https://github.com/abielli2020/Airbnb-Sentiment-Analysis.git
    ```

2.  Navigate to the `scripts/` folder and open the R Markdown file in RStudio.

3.  Run the script to reproduce the analysis.

------------------------------------------------------------------------

## Tools and Technologies

-   Programming Language: **R**
-   Libraries: `readr`, `dplyr`, `tidytext`, `ggplot2`, `tidyr`
-   Visualization: R-based plots and Tableau for visual storytelling (optional).

------------------------------------------------------------------------

## Author

**Alessandra Bielli**\
Connect with me on [LinkedIn](https://www.linkedin.com/in/alessandrabielli) or [GitHub](https://github.com/abielli2020).

Feel free to explore, fork, and contribute to this project!

------------------------------------------------------------------------
