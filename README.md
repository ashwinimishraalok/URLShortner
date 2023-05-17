# URLShortner

We can generate a unique hash og a given url using one of the has algorithm's present out there such as MD-5 or SHA-256
Multiple user can request to shorten the same original url , in that case the algorithm can generate the same hash for the url.

We can append a increasing number to the url before generating its hash, in that case the generated hash will always unique

How to run the application:

Ater connecting to the H2 database

we can hit the url like:
post http://localhost:8080/generate

Body :
{
  "url":"......"
 
}

output:

{
"originalUrl":"     ",
"shortLink":"  ",
"expirationDate": ""   

}

To go to the original url:

just go the the localhost:8080/shortLink

Thanks!
