# McDonald's Fast Food Nutrient Scraping Project

This repository contains a Jupyter Notebook that scrapes nutrient values from McDonald's fast food menu and processes the data to create a dashboard for identifying the healthiest menu options.

## Project Overview

The main goal of this project is to extract nutritional information (e.g., calories, fat, protein, carbs) from McDonald's menu items and visualize the data in a dashboard. The dashboard helps determine which menu options are the healthiest based on key nutritional criteria.

## Features

- Scrapes nutritional data from McDonald's website.
- Cleans and processes the data to make it suitable for analysis.
- Creates a dashboard to display the nutrient values of different menu items.
- Identifies the healthiest menu options based on user-defined criteria.

## Prerequisites

Before running this project, ensure you have the following dependencies installed:

```
pip install requests
pip install beautifulsoup4
pip install pandas
pip install matplotlib
pip install seaborn
pip install plotly
```

You can install the dependencies using the `requirements.txt` file (if included):

```
pip install -r requirements.txt
```

## Project Structure

The repository is structured as follows:

```
├── Scraping2.ipynb            # Jupyter Notebook for web scraping
├── requirements.txt           # Python dependencies (if included)
├── README.md                  # Project documentation
└── data/                      # Directory to store scraped data (if applicable)
```

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/mcdonalds-nutrient-scraping.git
   ```

2. Navigate to the project folder:

   ```bash
   cd mcdonalds-nutrient-scraping
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Scraping2.ipynb
   ```

4. Run the notebook cells to scrape data from McDonald's menu and process the nutrient values.

5. Use the final cells of the notebook to generate a dashboard that visualizes the healthiest options based on nutrient values.

## Customization

- Update the target website URL for McDonald's menu in the `requests.get()` function.
- Modify the scraping logic based on the website's HTML structure.
- Customize the dashboard visualizations by adjusting the charts or analysis criteria.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Requests Documentation](https://docs.python-requests.org/en/latest/)
- [Plotly Documentation](https://plotly.com/python/)
