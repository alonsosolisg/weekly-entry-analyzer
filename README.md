# Weekly Entry Analyzer

## Description

The Weekly Entry Analyzer is a Jupyter Notebook project that aims to analyze the sentiment, main topic, main keyword, and character count of weekly entries. It provides visualizations using matplotlib and created data points from the entries using several models like the TextBlob sentiment analysis and the ChatGPT 3.5 OpenAI API.

## Features

- Sentiment analysis using TextBlob
- Topic extraction using the ChatGPT 3.5 OpenAI API
- Keyword extraction using the ChatGPT 3.5 OpenAI API
- Character count analysis
- Visualizations using matplotlib

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/alonsosolisg/weekly-entry-analyzer.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Add your weekly entry data as pdf files in the /weekly_entries folder and name the files based on the date of the weekly entry with the following format: `DD-MM-YYYY.pdf`.

3. Open the `main.ipynb` notebook.

4. Follow the instructions in the notebook to analyze your weekly entries.
