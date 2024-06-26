
# EPL Match Winner Prediction Project

This project aims to predict the winner of football matches in the English Premier League (EPL).

## Project Steps

1. **Data Scraping:**
   - Scrape match data using `requests`, `BeautifulSoup`, and `pandas`.
2. **Data Cleaning:**
   - Clean the scraped data and prepare it for machine learning using `pandas`.
3. **Prediction Modeling:**
   - Make predictions about match outcomes using `scikit-learn`.
4. **Model Evaluation:**
   - Measure the accuracy of the predictions and improve the model.

## Code

The code for this project is available in the following Jupyter notebooks:

- [`scraping.ipynb`](scraping.ipynb) - Scrapes the match data from the web.
- [`predictions.ipynb`](predictions.ipynb) - Uses the scraped data to make predictions.

## Local Setup

### Installation

To set up the project locally, ensure you have the following installed:

- **JupyterLab**
- **Python 3.8+**
- **Python packages:**
  - `pandas`
  - `requests`
  - `BeautifulSoup4`
  - `scikit-learn`

You can install the required Python packages using the following command:

```bash
pip install pandas requests beautifulsoup4 scikit-learn
```

### Data

We will be scraping data from [FBref](https://fbref.com/en/) in the first part of the project (`scraping.ipynb`). If you only want to work on the prediction part of the project (`predictions.ipynb`), you can download the pre-scraped data (`matches.csv`) from the link below:

[Download `matches.csv`](https://drive.google.com/uc?export=download&id=1V1OHnqG29irN-56wf77LQvxhCY3HRfIy)

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, please contact Ryan Lee at rmlee1105@gmail.com.
