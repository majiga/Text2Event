# Text2Event repository
Event detection from domain-specific text data

### A survey paper for overview: Wei, Xiang & Wang, Bang. (2019). A Survey of Event Extraction from Text. IEEE Access. 
https://www.researchgate.net/publication/337638438_A_Survey_of_Event_Extraction_from_Text

![alt text](https://github.com/majiga/Text2Event/blob/master/images/survey_paper_overview.png)

![alt text](https://github.com/majiga/Text2Event/blob/master/images/survey_paper_RNNs.png)

## Files

### 1. source/extract_event_example.ipynb is a simple example file to extract events using pattern matching (trigger words)
- Detect events using trigger words
- Extract event details

### 2. source/graph_construction_from_text.ipynb does inormation extraction and graph construction
- Extract entities using a domain dictionary VOCABULARY_TYPED.json (https://github.com/majiga/OzROCK labelled dataset can be used for supervised named entity recognition)
- Extract relations
- Build a graph and visualise

![alt_text](https://github.com/majiga/Text2Event/blob/master/images/info_extraction.png)


... To be added


### Visualisation examples
Some graph visualisation that were created from mineral exploration reports: https://sites.google.com/view/majiga/case-studies

### Outcomes
1. List of events with their details
2. Visualisations to explore or discover events
3. Analysis, ...
4. Check other required outcomes stated by the unit in https://handbooks.uwa.edu.au/unitdetails?code=CITS5553

![alt text](https://github.com/majiga/Text2Event/blob/master/images/EventDetails.png)
