# leukemiascore
R-package which generate a leukemia score for genes known to be Pubmed cited in leukemia field.
---
usage 
>library(leukemiascore)
---
>set<-c("FLT3","TET2","MSH2")
---
>leukemia<-leukemiaquery(set)

### Starting the queries for the selected genes.

### Performing queries for leukemia literature 
	Number of papers found in PubMed for FLT3 was: 3001 
	Number of papers found in PubMed for TET2 was: 488 
	Number of papers found in PubMed for MSH2 was: 72 

### Performing queries for all the literature 
	Number of papers found in PubMed for FLT3 was: 5003 
	Number of papers found in PubMed for TET2 was: 1123 
	Number of papers found in PubMed for MSH2 was: 3890 
  
  
> leukemia


>leukemiafinal<-leukemiascore(leukemia)

> leukemiafinal

