# Zurich GitHub Users Analysis

This project scrapes GitHub's API for users in Zurich with over 50 followers, collecting user and repository details.

- **Data Collection and Cleaning**: The GitHub API was used to gather user profiles and repository data for Zurich-based users. Company names were cleaned, boolean values were normalized, and missing fields were handled to ensure a consistent dataset.
  
- **Data Insights**: A surprising insight was the high prevalence of repositories using `Python` and `JavaScript` among Zurich-based developers, reflecting a focus on web development and data-driven projects.

- **Developer Recommendation**: Developers could consider focusing on popular languages in Zurich, like Python and JavaScript, to increase local job opportunities based on the analysis of repository data.

## Project Overview
This project collects and analyzes GitHub user data for developers based in Zurich. The goal is to understand trends in technology use and provide insights that may benefit other developers.

## Data Collection and Processing
Using the GitHub API, we gathered public profiles and repository information for developers located in Zurich with more than 50 followers. Each profile was enriched with additional details, such as company, bio, and follower count. Data processing included:
- Cleaning up company names
- Normalizing boolean values to `true` and `false`
- Handling missing values to ensure a consistent dataset

## Instructions
To reproduce this analysis:
1. Clone the repository.
2. Run the `data_collection.py` script. It will output `users.csv` and `repositories.csv` files with all relevant data.

## Data Processing Script
The `data_collection.py` script includes all functions required for data collection, cleaning, and processing.

### Files in This Repository
- **users.csv**: Contains user data for GitHub users in Zurich.
- **repositories.csv**: Contains repository data for those users.
- **data_collection.py**: The main script for collecting and processing data.

## Insights from the Data
Our analysis revealed that Zurich-based developers focus on modern web and data science technologies. JavaScript, Python, and Java are the most commonly used languages. Additionally, repositories with higher star counts often include detailed documentation and are more likely to support collaborative features like wikis and project boards.

## Recommendations for Developers
Given the findings, developers looking to work in Zurich should prioritize learning JavaScript frameworks (such as React or Node.js) and Python for data science and backend development. Contributing to open-source projects and ensuring good documentation will likely improve repository engagement and visibility.
 
