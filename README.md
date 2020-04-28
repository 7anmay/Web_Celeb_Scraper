#Web_Celeb_Scraper
The dataset is built using the following steps:

Images:
1. Scrape popular website like Wikipedia to scrape out names and images of popular bollywood celebrities.
2. Use this scraped data to search in loop for each celebrity individually and specify the number of images to scraped for each celeb.
3. The images are filtered using a object detection model to discard images other than individual people.

Pesonality Data:
1. The Web is scraped for writeups and articles on the celeb which are compiled in a file.
2. The kea keyword extraction api helps us idetify keywords describing each celeb thus providing some insight into the personality of the celeb.
