### Node Microservice App
This is a basic microservice built with NodeJs

### Prerequisites

Begin by cloning the repository, `cd` into the cloned repository and run the following:

```
npm install
```
This command installs all the necessary dependencies


### Setup
Start up rabbitmq in your local machine


### Steps to run the application in this sequence
1. Start up service-registry
    npm start
2. start up feedback-service
    npm start
3. start up speaker-service
    npm start

4. Run conference app
    npm start

5. on browser go to
    `http://localhost:3080`