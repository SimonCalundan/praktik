# Fredag d. 9. Februar 


## Spontanlog 

I dag fik vi koblet sign-up flowet fra vores salgsside  sammen med samme flow 
på vores platform. Derefter testede vi det igennem en del gange, for at sikre
os at brugerne ikke ville løbe ind i dumme fejl når vi engang skal smide det op. 
Dette gjorde vi først ved selv at gå flowet igennem. Derefter satte jeg 
testing biblioteket Cypress op på vores salgsside, så jeg kunne e2e teste 
oprettelsesflowet på den side. 


## Reflektionslog 

### Frontend testing 
Udover at selve konfigurationen af testing biblioteket tog mig lidt over 1 time, 
grundet Cypress læste mit projekt som værende kodet med TypeScript frem for 
JavaScript, så var det en fed og lærerig oplevelse at prøver kræfter med et 
moderne testing bibliotek som Cypress. Det var meget brugervenligt, og alle 
test er skrevet i JavaScript med metoder som tilhører cy klassen. 
