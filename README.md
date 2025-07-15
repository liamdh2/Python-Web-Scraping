# Python Scraping & Analysis Projects

**Short Description:**  
A collection of three Jupyter notebooks demonstrating web scraping (stock data & a veterinary site) and graphical text analysis of a novel using Python.

## Notebooks

| Notebook                                    | Description                                                                                          |
|---------------------------------------------|------------------------------------------------------------------------------------------------------|
| **Graphical_Text_Analysis_of_Novel.ipynb**  | Text analysis on *Great Expectations*, including word‑frequency plots and sentiment over chapters.   |
| **NVIDIA_Stock_Data_Scraper.ipynb**         | Retrieves historical NVIDIA stock prices via the Alpha Vantage API and visualizes trends.            |
| **WebScraper_PetMed.ipynb**                 | Scrapes product and pricing data from the Wisdom Pet Medicine website for basic analysis.            |

## Getting Started

**Clone the repo**  
```bash
git clone https://github.com/yourusername/python-scraper-analysis.git
cd python-scraper-analysis
```

**Create and activate a virtual environment**  
```bash
python3 -m venv venv
source venv/bin/activate   # macOS/Linux
# or on Windows
venv\Scripts\activate
```

**Install dependencies**  
```bash
pip install -r requirements.txt
```

**Open the notebooks**  
```bash
jupyter lab
```  
or  
```bash
jupyter notebook
```

## Requirements

- Python 3.7+
- jupyterlab or notebook
- pandas
- matplotlib
- requests
- beautifulsoup4
- nbformat

*(Feel free to add additional libraries as needed for sentiment analysis, etc.)*
