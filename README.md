# mars_data_scrape_challenge
This is a project to analyze news content and data about Mars captured with html scraping

## Technologies
python, splinter[selenium], BeautifulSoup, html, lxml, pandas, matplotlib, jupyter

## Installation Guide
Follow splinter installation instructions (https://splinter.readthedocs.io/en/latest/install/driver_install.html) for preferred browser. BeautifulSoup needs to be installed.
All required installations can also be completed by running the following shell commands:
1. pip install "splinter[selenium4]"
2. pip install bs4
3. pip install html5lib
4. pip install lxml

## Usage
Run part_1_mars_news.ipynb to get text from the html and save to news_content.json.  Run part_2_mars_weather.ipynb to open up a website with Mars data and run analyses on the table. The notebook creates the mars_data_analysis directory to store the summary (mars_facts.txt) and dataframes (as csv's) used in the analyses.

![image](https://user-images.githubusercontent.com/119267098/222330776-36b5c820-2686-4d5e-a1c2-855578518837.png)

![image](https://user-images.githubusercontent.com/119267098/222330813-a61d5ec8-f09e-4399-872c-74402d9c626f.png)

![image](https://user-images.githubusercontent.com/119267098/222330838-07e48ce3-6993-468e-ba0c-a4388040327e.png)

## Contributors
Developed by Luis Hernandez Email: lhernandez.mag.89@gmail.com

## License
UC Berkeley Extension Data Analytics Program
