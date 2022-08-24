# DAT250-Lab1Week1

## Instalation 
I had already installed all the programs that was requierd. However a program that was not listed was not on my machine.I did not have brew installed. I downloaded brew, it took some time but then i had no problems finishing the installation.

## Validated
Tried to open the http://localhost:5002, this was not working for some reason. 
Then i tried to open http://127.0.0.1:5002 and got the confirmation that everything was ok. 

## Technical problems encountered with the Heroku
I had some problem when i came to the "Prepare the Local Environment", i had something on port 5000 that i did not manage to terminate so i needed to find the application.properties file where i could change to port to 5002. 

## Pending issues
The Define Config Vars did not run correctly. The line "String energy = System.getenv().get("ENERGY");" only got value null and not the correct value from the .env file, tried to fix this but could not get this to work correctly. 
It worked in the web after i had committed the changes, so i may have some problems whith my file structure somewhere.. 

Link to Heroku app: https://secret-sierra-09497.herokuapp.com/hello?fbclid=IwAR2trApZduFZPIgWUAJgB1A7D05EGpEcdv7gvNa4XZMSM1KZgeGokeEK82g
