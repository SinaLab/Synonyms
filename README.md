# Synonyms Dataset
The dataset is a set of 500 synsets (extracted from the Arabic Wordnet). Each synset is enriched with a list of candidate synonyms. The total number is 3K candidates. Each candidate synonym is then annotated with a fuzzy value by four linguists (in parallel). The dataset is important for understanding how much linguists (dis/)agree on synonymy (which we found RMSE: 32% and MAE: 27%). In addition, we used the dataset as a baseline to evaluate our algorithm. See the scoring guidelines, figures, and details in the paper section 3.<br />

License: MIT

# Online Demo
You can try our algorithm using the demo link below <br />
https://portal.sina.birzeit.edu/synonyms/

![Alt text](https://portal.sina.birzeit.edu/synonyms/synonyms_screenshot.PNG)


Model Training
--------

    @inproceedings{GJJB23,
title = {A Benchmark and Scoring Algorithm for Enriching Arabic Synonyms},
author = {Sana Ghanem and Mustafa Jarrar and Radi Jarrar and Ibrahim Bounhas},
isbn = {978-9-464027-31-0},
booktitle = {Proceedings of the 12th International Global Wordnet Conference (GWC2023)},
pages = {},
location = {San Sebastian},
month = {Jan},
year = {2023},
publisher = {Global Wordnet Association},
keywords ={Synonyms, Synset, WordNet, Dictionary, Arabic, Multilingual lexicons, Online dictionary, Language resources, Lexical semantics, NLP},
abstract = {Synonymy relationships are used in many NLP tasks and knowledge organization systems. However, automatic synonym extraction is a challenging task, especially for low-resourced and highly ambiguous languages such as Arabic. This paper addresses the task of extending a given synset with additional synonyms taking into account synonymy strength as a fuzzy value. In other words, given a mono/multilingual synset and a threshold (a fuzzy value $[0-1]$), our goal is to extract new synonyms above this threshold from existing lexicons. We present twofold contributions: an algorithm and a benchmark dataset. The dataset consists of 3K candidate synonyms for 500 synsets. Each candidate synonym is annotated with a fuzzy value by four linguists. The dataset is important for (i) understanding how much linguists (dis/)agree on synonymy, in addition to (ii) using the dataset as a baseline to evaluate our algorithm. Our proposed algorithm extracts synonyms from existing lexicons and computes a fuzzy value for each candidate. Our evaluations (using the one-way ANOVA test) show that the algorithm behaves like a linguist and its fuzzy values are close to those proposed by linguists (using RMSE and MAE).},
url={http://www.jarrar.info/publications/GJJB23.pdf}
}



# Credits
This research is funded by the Research Committee at Birzeit University (No. 2021/49)

# Citation
Sana Ghanem, Mustafa Jarrar, Radi Jarrar, Ibrahim Bounhas: [A Benchmark and Scoring Algorithm for Enriching Arabic Synonyms](http://www.jarrar.info/publications/GJJB23.pdf). In Proceedings of the Global WordNet Conference (gwc2023), Donostia, January. 2023
