# Mandag d. 19 Februar


## Spontanlog 

I dag har jeg kigget lidt på vores backends tech stack, samt undersøgt og 
implementeret et nyt frontend testing framework

Ift vores backend læste jeg op på Celery for Python. Celery er et bibliotek til
Python, som gør det muligt at distrubere opgaver til adnre servere. Derudover 
kan man Schedule ens opgaver, så de kører på specifikke tidspunkter, eksempelvis
Cernels statistisk som kører hver nat.

Udover Celery har jeg også implementeret Sentry til vores Frontend. 
Sentry er ikke et direkte testing framework, men derimod en applikations overvågnings
software, som man forbinder direkte til sit projekt, i dette tilfælde vores 
next.js projekt. 

## Reflektionslog 


### Frontend testing 
At installerer Sentry har givet utroligt meget værdi til vores udvikling. Det 
er nu muligt for os at se direkte replays af hvilke fejl kunder har løbet ind i
samt hvilke netværkskald og console output der var under fejlen


### Backend viden
At læste op på celery svarede på mange spørgsmål jeg havde ift. vores backends 
opgbygning. Jeg havde altid undret mig over hvordan vi kørte vores statistik, samt 
hvordan alle vores netværkskald blev fordelt ud.
