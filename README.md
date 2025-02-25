# YouTube Finance Data Analysis

This project focuses on scraping, cleaning, and analyzing trending finance-related YouTube videos to extract insights.

## Project Structure

```
📂 YOUTUBE_FINANCE_DATA_INSIGHTS
├── venv/                     # Virtual environment
├── cleaned_youtube_finance.csv # Cleaned dataset
├── Data_Cleaning.ipynb        # Data cleaning process
├── EDA.ipynb                  # Exploratory Data Analysis (EDA)
├── README.md                  # Project documentation
├── requirements.txt           # Required dependencies
├── youtube_finance_trending.csv # Raw scraped dataset
└── YT_Scrapper.ipynb          # Web scraper for YouTube finance data
```

## Setup Instructions

### 1. Clone the Repository
```sh
git clone <repository_link>
cd YOUTUBE_FINANCE_DATA_INSIGHTS
```

### 2. Create and Activate Virtual Environment
```sh
python -m venv venv
# Activate on Windows:
venv\Scripts\activate
# Activate on Mac/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

## Workflow

1. **Scraping Data**: `YT_Scrapper.ipynb` extracts trending finance videos.
2. **Cleaning Data**: `Data_Cleaning.ipynb` preprocesses the raw dataset.
3. **Exploratory Data Analysis (EDA)**: `EDA.ipynb` visualizes insights from cleaned data.
4. **Final Dataset**: `cleaned_youtube_finance.csv` stores structured data for analysis.

## Features
- Scrapes trending finance videos from YouTube.
- Cleans and processes video titles, views, and channel details.
- Performs exploratory analysis on video popularity and trends.

## License
This project is for educational purposes only. All data is sourced from YouTube for analysis.

