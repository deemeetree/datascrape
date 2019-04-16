# datascrape

`WikipediaScrape-ContestedNeutrality.ipynb`

This script will scrape some of the articles on https://en.wikipedia.org/w/index.php?title=Category:All_NPOV_disputes page which contains all the articles that have contested neutrality. It will save it into an XML file which can then be processed by https://gitlab.com/mattiasostmar/discoursediversity to identify correlation in the diversity of the discourse and NPOV measures. NPOV is set to FALSE here.


`WikipediaScrape-GoodArticles.ipynb`

This script will scrape some of the articles on https://en.wikipedia.org/wiki/Wikipedia:Good_articles/all page which contains all the articles that have been marked as "good". We assume that they have sufficient neutrality score (NPOV - neutral point of view). It will save it into an XML file which can then be processed by https://gitlab.com/mattiasostmar/discoursediversity to identify correlation in the diversity of the discourse and NPOV measures. NPOV is set to TRUE here.

