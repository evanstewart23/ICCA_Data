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
* Group Name as reported by V.V. A process of data cleaning implemented standardized spelling for groups across years.
* University as reported by V.V., again standardized in data cleaning
* Score - numeric score for each placing group reported by V.V.
* Place - a numerical designator for rank in each competition. Score reflects place in most cases, but the rank designator preserves changes in rank due to scoring penalties such as going over time. 
* Award - a count of the number of special awards given to placing group  in each competition (e.g. best choreography, outstanding soloist). 
* Gender - an indicator of the stated gender composition of each group (all men, all women, coed), validated by group descriptions obtained via Google. 
