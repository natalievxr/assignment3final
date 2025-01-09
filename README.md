# Assignment 3 final

This assignment includes a corpus of tracks from Taylor Swift's album folklore. The data was scraped from https://www.azlyrics.com/t/taylorswift.html. I chose the album folklore specifically as this album marked a shift in Swift's style of songwriting, and was a huge moment for pop culture.

For the songwriting credits, the data was scraped from https://taylorswift.fandom.com/wiki/Folklore. 

This repository contains
- Read me file
- CSV file with columns containing the track number, track name, lyrics and the writing credits
- Jupyter Notebook explaining step by step how I scraped the data, and it answers a simple question posed in the beginning of the notebook

Terms and conditions for web scraping: There was a comment in the page source that said "Usage of azlyrics.com content by any third-party lyrics provider is prohibited by our licensing agreement. Sorry about that." 

From my understanding, as I am not a third party lyric provider, and because I do not intend on publishing the data for commercial use, it was acceptable for me to continue with web scraping this website. As I was scraping data, I noticed that AZlyrics had restrictions in place where you could not scrape large amounts of data at a time otherwise it would block your IP address and deny you access, hence why the lyrics column is incomplete as the website blocked me. Before permanently blocking me, the website would ask me to tick a box saying "I am not a robot" which just tracks my laptop activity to see if it was unnatural. Naturally, I passed each I am not a robot test, however when it came to scraping the lyrics, which is a huge chunk of data, it began to block me unprovoked. I assumed it thinks I am a robot, and not that web scraping is not allowed, as there were many projects online that scraped data from AZlyrics too. To be very sure, I have sent an email to the AZlyric team, informing them about this assignment, and luckily I have received their permission.
