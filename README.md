# Text2Event: Event detection from domain-specific text data

### A survey paper for overview: Wei, Xiang & Wang, Bang. (2019). A Survey of Event Extraction from Text. IEEE. 
https://www.researchgate.net/publication/337638438_A_Survey_of_Event_Extraction_from_Text

## WAMEX Dataset
https://www.dmp.wa.gov.au/WAMEX-Minerals-Exploration-1476.aspx

## Files

### 1. Text classification using different machine learning algorithms
source/20news_classification.ipynb

![alt_text](https://blogs.sas.com/content/subconsciousmusings/files/2017/04/machine-learning-cheet-sheet-2.png)
Source: https://blogs.sas.com/content/subconsciousmusings/files/2017/04/machine-learning-cheet-sheet-2.png

### 2. source/extract_event_example.ipynb is a simple example file to extract events using pattern matching (trigger words)
- Detect events using trigger words
- Extract event details

### 3. source/graph_construction_from_text.ipynb does inormation extraction and graph construction
- Extract entities using a domain dictionary source/VOCABULARY_TYPED.json (https://github.com/majiga/OzROCK labelled dataset can be used for supervised named entity recognition; Dictionary folder also contains the 6 lists of entities.)
- Extract relations
- Build a graph and visualise

![alt_text](https://github.com/majiga/Text2Event/blob/master/images/info_extraction.png)

### 4. source/visualisation_WA.ipynb visualises the data/events.csv file on the WA map
- Read data/events.csv file
![alt_text](https://github.com/majiga/Text2Event/blob/master/images/event_list.png)

- Visualise the events on the WA map (data/map_WA.csv file can be useful for getting latitude and longitude data)
![alt_text](https://github.com/majiga/Text2Event/blob/master/images/vis_map.png)


### Visualisation examples
Some graph visualisation that were created from mineral exploration reports: https://sites.google.com/view/majiga/case-studies

Graph from text demo: https://nlp-tlp.org/text2kg/
- Source code for the demo: https://github.com/majiga/text2kg-uwa
- Paper for the demo: https://arxiv.org/pdf/1909.01807.pdf

### NLP tools:
spacy.io

### Outcomes
1. List of events with their details
2. Visualisations to explore or discover events
3. Analysis, ...
4. Check other required outcomes stated by the unit in https://handbooks.uwa.edu.au/unitdetails?code=CITS5553

![alt text](https://github.com/majiga/Text2Event/blob/master/images/EventDetails.png)
