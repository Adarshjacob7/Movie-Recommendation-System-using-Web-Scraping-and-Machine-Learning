<h1>Movie Recommendation System using Web Scraping & Machine Learning</h1>

 ### [LINK TO BE UPLOADED]()

<h2>Description</h2>
This project builds an end-to-end movie recommendation system by combining web scraping, API integration, data processing, and machine learning.

I first scraped worldwide box office data from Box Office Mojo using Python (Requests + BeautifulSoup), extracting key financial metrics such as worldwide, domestic, and foreign collections along with their percentages. The scraped data was cleaned, structured, and stored as a CSV dataset.

Next, I enriched this dataset by integrating the OMDb API, fetching additional movie metadata including IMDb ratings, directors, cast, genres, certifications, vote counts, and plot descriptions.

Using the merged dataset, I developed a content-based recommendation model. Movie features were combined into a single text representation and vectorized using TF-IDF, with cosine similarity used to measure movie-to-movie relevance. Given 5 input movies, the model recommends 10 similar movies based on thematic and metadata similarity. 

<br />

<h2>Data Collection</h2>

- **Web Scraping:**  
  Scraped worldwide box office data from **Box Office Mojo** using Python (Requests + BeautifulSoup).  
  Extracted movie titles, worldwide, domestic, and foreign collections with percentages.

- **API Integration:**  
  Enriched the dataset using the **OMDb API** to fetch IMDb ratings, directors, cast, genres, certifications, votes, and plot summaries.

<br />

<h2>Feature Engineering & Model</h2>

- Combined multiple text features into a single column
- Vectorized text using **TF-IDF**
- Used **cosine similarity** for content-based recommendations
- Proper ML workflow with train-test split

<br />

<h2>Recommendation Logic</h2>

- Accepts **5 input movies**
- Computes similarity against the entire dataset
- Returns **top 10 similar movies**
- Excludes input movies from results

<br />

<h2>Tech Stack</h2>

- Python
- Requests & BeautifulSoup – Web Scraping
- Pandas & NumPy – Data Processing
- OMDb API – Data Enrichment
- Scikit-learn – TF-IDF, Cosine Similarity
- Machine Learning – Content-Based Filtering

<br />

<h2>Author</h2>

Adarsh Joshua
Data Analytics & Machine Learning Enthusiast

<br />

<h2>IGNORE THIS:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
