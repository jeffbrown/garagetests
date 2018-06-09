# Garage Geb Tests

This project contains [Geb](https://gebish.org) tests for the Garage
 application described at [guides.grails.org/building-a-react-app/guide/](http://guides.grails.org/building-a-react-app/guide/index.html).
 
## Checkout The Garage Application Source Code

    git checkout https://github.com/grails-guides/building-a-react-app.git
    
If you do not have `git` installed you may instead download the latest
code from [https://github.com/grails-guides/building-a-react-app/archive/master.zip](https://github.com/grails-guides/building-a-react-app/archive/master.zip).

## Run The Garage Application

From the `building-a-react-app/complete/` directory run the Garage
application:

    cd building-a-react-app/complete/
    ./gradlew bootRun
    
## Run The Tests In This Project

The tests should be run from the project which contains the `README.md`
file that you are reading right now, not the `building-a-react-app` project.

    ./gradlew -Dgeb.env=chrome test 
