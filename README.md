# Web Celeb Scraper 

One Paragraph of project description goes here

## Getting Started
### Overview
The code executes the following steps to buid the dataset, it is divided into two parts:
Images:
1. Scrape popular website like Wikipedia to scrape out names and images of popular bollywood celebrities.
2. Use this scraped data to search in loop for each celebrity individually and specify the number of images to scraped for each celeb.
3. The images are filtered using a object detection model to discard images other than individual people.

Pesonality Data:
1. The Web is scraped for writeups and articles on the celeb which are compiled in a file.
2. The kea keyword extraction api helps us idetify keywords describing each celeb thus providing some insight into the personality of the celeb

### Prerequisites

You just need to install the requirements.txt file in the repo to get all the prerquisites.
Also before that you may want to make a virtual environment for running and development purposes. If you already have that
set up and running you should move ahead otherwise you can refer [virtualenv](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/) or [conda](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)

```
pip install requirements.txt
```
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
