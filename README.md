# Web-Scrapping using Beautifulsoup

Projek ini dikembangkan sebagai salah satu bentuk pengembangan diri dalam ilmu data. Hasil akhir yang diharapkan dari projek ini adalah melakukan simple webscrapping untuk mendapatkan informasi dari website. Dalam projek ini juga Kita akan memanfaatkan flask dashboard sederhana untuk menampilkan hasil scrap dan visualisasi kita.

## Dependencies

Pastikan untuk melakukan instalasi beberapa librari berikut:

- beautifulSoup4
- pandas
- flask
- matplotlib

Atau cukup menginstall requirements.txt dengan cara berikut

```python
pip install -r requirements.txt
```


## What You Need to Do

* Silahkan mencoba melakukan scraping menggunakan `beautiful soup` di notebook terlebih dahulu.
* Untuk tag informasi yang ingin didapatkan dapat disesuaikan.


```python
 main_webpage = soup.find(____)
 box_movie = soup.find_all(___)
```

* Isi bagian ini untuk menyimpan hasil informasi yang sudah berhasil didapatkan menjadi sebuah dataframe.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```

* Terakhir anda dapat menggunakan fungsi `scrap` dengan cara mengisi bagian berikut dengan link url web yang anda inginkan.

```python
dataset_movie = scrap(___) #insert url here
```

* Bapak/Ibu juga dapat bermain dengan UI nya pada `index.html` yang dimana Bapak/Ibu dapat mengikuti comment yang ada untuk mengetahui bagian mana yang dapat diubah. 

### Data Resource

1. Data film yang rilis di tahun 2019 dari `imdb.com/search/title/?release_date=2019-01-01,2019-12-31`

    * Dari Halaman tersebut carilah `judul` , `imdb rating` , `metascore`, dan `votes`
    * Membuat plot dari 7 film paling populer di tahun 2019.


Happy learning! 
