


![](https://github.com/Envixlab/OpenMice/blob/master/OpenMICE.jpg)

 
 
## OpenMice

By Paniccia, C., M. Di Febbraro, L. Delucchi, R. Oliveto, M. Marchetti, and A. Loy. 

30 July 2018

Provided in support of the Data-paper:

>OpenMICE: an open spatial and temporal dataset of small mammals in South-Central Italy based on owl pellet data 
by Paniccia, C., M. Di Febbraro, L. Delucchi, R. Oliveto, M. Marchetti, and A. Loy. 2018. Ecology.



We would appreciate that researchers cite this paper if using all or part of the datasets. We also request that researchers and teachers inform us of how they are using the data. 
Correspondence and requests for materials should be addressed to Chiara Paniccia (email: c.paniccia@unimol.studenti.it).



You can download our dataset in SQLite format!

###
- I want to read/cite the preprint describing OpenMICE.→ https://doi.org/10.1002/ecy.2506
- I want to reference the SQLite version of OpenMICE.→ [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1342403.svg)](https://doi.org/10.5281/zenodo.1342403) - Please also cite our preprint.

## Description

OpenMice is the first standardized and accessible georeferenced database of small mammal occurrences, abundances and functional traits in South-Central Italy.

Small mammal occurrences derived from owl pellets were obtained from different sources, including original field surveys, publications, grey literature, existing databases and museum collections. We first performed a data-gathering and then georeferenced available sites from five owl species occurring in Italy (i.e. *Asio otus*, *Athene noctua*, *Bubo bubo*, *Tyto alba*, *Strix aluco*). Additionally, for each small mammal species, with an exhaustive literature review, we recorded abundance at each site and some functional traits such as body mass, trophic level, litter size, prevalent habit etc…

We stored data into a relational database, i.e. a set of tables related each other: OpenMice was designed by normalization rules to minimize redundancy and dependency and to isolate data. This means that design changes (e.g. modifications of a field) can be made in just one table and then be automatically propagated throughout the database. Given the long-term support for data storage, new information data can be added and the database can be expanded to include other geographical contexts.


![](https://github.com/Envixlab/OpenMICE/blob/master/OpenMICE_schema.jpg)


**Structure of the relational OpenMICE database. A primary key (key icon) uniquely identifies each record (row) in a specific table, and one or more attributes can be associated with each primary key. A foreign key links to a primary key in another table and is used to create relationships between tables. Relationships among tables reduce redundancy and guarantee data consistency.**

