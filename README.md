# APITest

API test

Website link : https://restful-booker.herokuapp.com

Requirements

JDK 8 Install (Link: https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)


Node JS Install (Link: https://nodejs.org/en/)


Environment Variable Setup

Postman (Link: https://www.postman.com/)
Method:

        1. Post

        2. Get
        
        3. Put

        4. Delete


API :
        1. https://restful-booker.herokuapp.com/booking/

        2. https://restful-booker.herokuapp.com/booking/id

        3.  https://restful-booker.herokuapp.com/auth

        4. https://restful-booker.herokuapp.com/booking/1
Newman 
Install Command: npm install -g newman


Run Command: 


newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
newman run “Collection Link” -e “Path”/EnvironmentName.json

Report:


Install: npm install -g newman-reporter-html

	npm install -g newman-reporter-htmlextra
Run Command: 


newman run “Collection Link” -e EnvironmentName.json -r cli,html
newman run “Collection Link” -e EnvironmentName.json -r cli,htmlextra




