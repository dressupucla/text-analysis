## Text-mining, Text-analysis: distant reading & close reading

**Research Question**: What themes occur in the documents collected in the [First Person Narratives](https://docsouth.unc.edu/fpn/) in the “Documenting the American South” collection? 

This collection offers "many Southerners' perspectives on their lives by presenting letters, memoirs, autobiographies and other writings by slaves, laborers, women, aristocrats, soldiers, and officers.”

https://docsouth.unc.edu/fpn/texts.html   We can navigate the collection [by subject](https://docsouth.unc.edu/browse/subject/index.html?letter=R), but that often won’t help us with themes that are more nuanced. E.g. How is slavery depicted?  

### Part A: Text mining: Unsupervised Learning -- what can a computer “learn”? We’re not telling it, at least initially, which words to look for.  

#### Terminology for Topic-Modeling:    
* Documents: texts in separate files
* Topics: themes made up of words that occur with each other in the same documents 
* Model: the proportion of topics in a document within a corpus of documents. A model provides a distant-view of an entire corpus, or collection of texts.  Each document has a list of topics and their proportions, e.g. Document 1 includes 20% of Topic A, 50% of Topic B.    

#### Example of how topic modeling can be used: 
* Find similar/dissimilar texts: In full-text databases, such as Web of Science, JStor, etc, we can cluster articles based on this model (thematic profile), without relying upon metadata that might be outdated.  

