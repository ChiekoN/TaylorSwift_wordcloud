# Taylor Swift wordcloud in Python
![TopImage](images/TopImage.jpg)

I created wordclouds from Taylor's song lyrics.

I wanted to visualise the tendency and frequency of words that appear in her songs for each album. As it's well-known, each of her albums is very distinctive to each other with regard to the concept, music genre, and background of the stories told in lyrics. They represent the **Eras** in her music career and her own experience at the time in her life.

I am a fan of Taylor, I love her music, and I got an idea that it would be interesting to create wordclouds for each of her albums from the lyrics, and hopefully I can see some similarities and differences between them in terms of word choices and frequencies.

In short, I just wanted to create some awesome visualisation that represents her masterpieces!

## Challenges

I had two challenges in this project:

1. `get_spotify_data.ipynb`

    Get Taylor's all albums and lyrics data from [Spotify Web API](https://developer.spotify.com/documentation/web-api) and [Genius API](https://docs.genius.com/).
    I stored the list of albums and songs in `.csv` files, and actual album data including lyrics in JSON files locally. 

    NOTE: Some client IDs and the access token have been stored in my local `config.py`, which is not in this repository for security reasons. If you would like to run this notebook, please create your own *config.py*.

2. `create_wordclouds.ipynb`

    Retrieve the lyrics of all songs in an album with removing unnecessary characters at the start and the end of the lyrics. Concatenate all the album lyrics into one text string, and pass it to the [Python wordcloud generator](https://pypi.org/project/wordcloud/#description).


## Results

Here are the results! I placed 10 albums in descending order of time in which the songs were written and the album was originally published. (However, I chose *Taylor's version* for those that have them to acquire lyrics including *from the Vault*, assuming they were also written when the album was created originally)

### Midnights (3am Edition)
<img src="images/Midnights%20(3am%20Edition).jpg" alt="Midnights" width=500>

### evermore (deluxe version)
<img src="images/evermore%20(deluxe%20version).jpg" alt="evermore" width=500>

### folklore (deluxe version)
<img src="images/folklore%20(deluxe%20version).jpg" alt="folklore" width=500>

### Lover
<img src="images/Lover.jpg" alt="Lover" width=500>

### reputation
<img src="images/reputation.jpg" alt="reputation" width=500>

### 1989 (Taylor's Version)
<img src="images/1989%20(Taylor’s%20Version).jpg" alt="1989" width=500>

### Red (Taylor's Version)
<img src="images/Red%20(Taylor’s%20Version).jpg" alt="1989" width=500>

### Speak Now (Taylor's Version)
<img src="images/Speak%20Now%20(Taylor’s%20Version).jpg" alt="SpeakNow" width=500>

### Fearless (Taylor's Version)
<img src="images/Fearless%20(Taylor’s%20Version).jpg" alt="Fearless" width=500>

### Taylor Swift
<img src="images/Taylor%20Swift.jpg" alt="TaylorSwift" width=500>










