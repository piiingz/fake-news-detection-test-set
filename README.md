# A small manually fact-checked fake news dataset

> A balanced and cleaned fake news dataset with fact-checked labels suitable as a test set for fake news classification tasks.

### Dataset information 
* Consists of in total 434 articles, 217 of each class 
* Articles are mainly from 2017 and 2018, but some are from before 2017
* The articles in this dataset have been manually cleaned to remove empty articles/titles, advertisement etc. 

The dataset is assembled from three different datasets:
1.  [FakeNewsNet](https://github.com/KaiDMML/FakeNewsNet) (The Politifact dataset) - 217 fake and 73 real articles 
2.  [MisInfoText](https://github.com/sfu-discourse-lab/MisInfoText) (The Snopes dataset) - 58 real articles
3.  Manually gathered articles from [Snopes.com](https://www.snopes.com/fact-check/) - 86 real articles
 
 
 The dataset contains the following features:
 * `id` - original label from the origin dataset
 * `label` - 0 = real, 1 = fake
 * `url` - url of the article
 * `title` - article title
 * `content` - article content

### Disclaimer
This dataset was assembled as part of a master thesis, and we can not vouch for the correctness of all labels. 
 
