
![screenshot](Genius-Webscrape/screenshot.png)

# Genius Webscrape - A Sentiment Analysis of Taylor Swift versus Selena Gomez

## Introduction

This project explores the sentiment and subjectivity of Taylor Swift’s music over time, with a comparative baseline against Selena Gomez.

Taylor Swift has transformed from a small-town country artist to a ten-time Grammy Award-winning pop icon. Alongside her success, her career has been marked by highly publicized controversies, which may have influenced both the themes and emotional tone of her songwriting.

The central goal of this project was to analyze how Swift’s lyrics have evolved in terms of **sentiment** (positive vs. negative) and **subjectivity** (personal and emotional vs. objective and general). To contextualize these findings, Selena Gomez—a fellow pop star with a less scandal-focused public image—was chosen as a point of comparison.

---

## Hypothesis

- **Taylor Swift**: Lyrics may show greater personal subjectivity and fluctuating sentiment reflecting her public experiences.  
- **Selena Gomez**: Lyrics may lean toward more objective themes with a more consistently positive sentiment.

---

## Methods

- **Data Collection**: Lyrics were scraped using the LyricGenius API.  
- **Data Storage**: All lyric data was stored in `.json` and `.csv` files included in this repository.  
- **Analysis**: Sentiment analysis was performed to measure polarity (positive vs. negative) and subjectivity (personal vs. objective).

---

## Repository Contents

- `data/` – JSON and CSV files of scraped lyrics (Taylor Swift & Selena Gomez).  
- `notebooks/` – Jupyter notebooks with sentiment analysis and visualization.  
- `src/` – Python scripts for scraping, preprocessing, and analysis.  
- `results/` – Output plots and tables generated during the project.

---

## Technologies Used

- **Python**  
- **Pandas** (data wrangling)  
- **TextBlob / NLTK** (sentiment analysis)  
- **LyricGenius API** (data collection)  
- **Matplotlib / Seaborn** (visualization)  

---

## Conclusion

This project provides a comparative look at how public perception and personal experience might manifest in song lyrics. The findings may support or challenge the initial hypothesis about the lyrical differences between Taylor Swift and Selena Gomez.