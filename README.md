# Getting started with Google App Engine and Spring Boot in 5 steps
===========================

Link to [Getting started with Google App Engine and Spring Boot in 5 steps](https://medium.com/google-cloud/getting-started-with-google-app-engine-and-spring-boot-in-5-steps-2d0f8165c89) medium.com article . 

How to run/deploy
-----
- Test locally

mvn appengine:run

- Create Google App Engine app

gcloud config set project {PROJECT_ID}

gcloud app create --region us-central

- Deploy to Google App Engine app

mvn appengine:deploy

- Open in browser

gcloud app browse

- Update project

mvn appengine:deploy

Link to project
-----
[https://spring-gae-project.appspot.com/](https://spring-gae-project.appspot.com/)