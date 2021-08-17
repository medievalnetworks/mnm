---
layout: page
title: Technical Overview
---

### Digital Choices
 
For a project like the Medieval Networks of Memory, which involved coordination between time zones and continents as well as formats and various forms of digital facsimiles, we needed solutions that are at the same tested and innovative.

The initial data gathering was made on the basis of Jean Dufour’s edition of both rolls. We used Google Drive and Google Sheets to cooperate, enter data, and store additional information, but all the operations on data itself, including quality testing, were done outside of Google’s web interface. Choosing Google is always a trade-off, and we were aware of its drawbacks, but it allowed us to cooperate in pandemic conditions and allowed all members of the team to start from day one.
The actual data cleaning, quality control and analysis was done on exported .csv files in R. We have used a variety of packages, including udpipe for tokenization and BTM for topic modelling (especially because the tituli of our rolls are relatively short texts) paired with our own Latin stopwords collection.

The mapping of both rolls was done using a combination of leaflet and mapview. We needed a solution that could incorporate multiple layers of data reflecting the multifaceted nature of the information that we have gathered. A crucial condition was the ability to include both manuscript images and the transcription of the tituli. The result, two interactive maps allowing users to explore the results of our research, is also scalable, allowing for inclusion of further layers in the future. The maps are easy to use and require minimal prior knowledge while containing a substantial amount of information. Thus, they are useful for both researchers and members of the public interested in mortuary rolls, female agency and palaeography of the thirteenth century.

Finally, the website that we used to deploy our research and the interactive maps was built on Github Pages for the ease of use, ability to easily host self-contained interactive objects and accessibility.
