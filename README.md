# Forum Question Analyzer

This project utilizes Big Data techniques to analyze questions from Stack Exchange forum. 
Using the Stack Exchange Data Dump from archive.org, it predicts whether a question will receive an accepted answer.

## Data Source
The data is obtained from the Stack Exchange Data Dump, available [here](https://archive.org/download/stackexchange/). Our project uses the [TeX forum data](https://archive.org/download/stackexchange/tex.stackexchange.com.7z).

## Setup
1. Download the Stack Exchange Data Dump from [archive.org](https://archive.org/download/stackexchange/tex.stackexchange.com.7z).
2. Extract the data dump into the `tex.stackexchange.com` folder.
3. Install Python 3.8 or higher.
4. [Install Spark](https://spark.apache.org/docs/latest/) (3.5.0 recommended).
5. Install the required dependencies: `pip install -r requirements.txt`.
6. Run jupyter notebook and open `analysis.ipynb`, `features.ipynb` or `statistics.ipynb` to see the results of our analysis.

## Results
Our model achieved an accuracy of 74.24% in predicting accepted answers.

## Contributors
- Krzysztof Mizgała
- Julia Czerniecka
- Wiktoria Gałdusińska
- Jerzy Grunwald
- Maciej Kosierb

Feel free to contribute and improve our project!
