# Web-Scrapping using Beautifulsoup

This project was developed as a form of self-development in data science. The final result expected from this project is to do simple webscrapping to get information from the website. In this project we will also use a simple dashboard flask to display our scrap and visualization results.

## Dependencies

Make sure to install the following libraries:

- beautifulSoup4
- pandas
- flask
- matplotlib

Or simply install requirements.txt in the following way

```python
pip install -r requirements.txt
```


## What You Need to Do

* Please try scraping using `beautifulsoup` on the notebook first.
* The tag information you want to get can be adjusted.

```python
 main_webpage = soup.find(____)
 box_movie = soup.find_all(___)
```

* Fill in this section to save the information that has been successfully obtained into a dataframe.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```

* Finally, you can use the `scrap` function by filling in the following section with the web url link you want.

```python
dataset_movie = scrap(___) #insert url here
```

* You can also play with the UI in `index.html` where you can follow the comments to see which parts can be changed.

### Data Resource

1. Data for films released in 2019 from `imdb.com/search/title/? Release_date = 2019-01-01,2019-12-31`

     * From this page, look for `title`,` imdb rating`, `metascore`, and` votes`
     * Make plots of the 7 most popular films of 2019.
     
Happy learning! 
