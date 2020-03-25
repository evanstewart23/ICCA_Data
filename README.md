# ICCA_Data
Tidy data set of public results from Varsity Vocals' ICCA competitions

ICCA Competition Data Set 2006-2019
Version 1.0  
May, 2019
Compiled by [Evan Stewart](https://www.twitter.com/@evanstewart23)

CSV includes ICCA scoring data for top three placing a cappella groups in tidy format from all reported competitions by [Varsity Vocals](https://varsityvocals.com/results-page/). Data collection began at 2006, the first year V.V. reports scores for all Quarterfinal competitions, as well as Semifinal and Final scores. 

Variables include:  

* Year of Competition
* Region of Competition as classified by V.V.
* Competition Level - Quarterfinal, Semifinal, or Final
* compcode - a numerical designator to distinguish multiple quarterfinals within regions. Regional Semifinals and Finals receive a compcode of 1. 
* Group Name as reported by V.V. data cleaning for v0.5 standardized spelling for groups across years. R's str to upper command further standardizes these names with uniform uppercase. 
* University as reported by V.V., again standardized in v0.5 cleaning
* Score
* Place - a numerical designator for rank in each competition. Score reflects place in most cases, but the rank designator preserves changes in rank due to scoring penalties such as going over time. 
* Award - a count of the number of special awards given to placing group  in each competition (e.g. best choreography, outstanding soloist). 
* Gender - an indicator of the stated gender composition of each group (all male, all female, coed), validated by group descriptions obtained via Google. 
