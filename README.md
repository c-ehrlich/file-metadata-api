# [File Metadata Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/file-metadata-microservice)

A basic API that returns metadata information on uploaded files.

Part of the FreeCodeCamp Back End Development Certification.

## Installation
* Clone down the repo
* `npm i`
* `npm start`

## Sample deployment
https://fcc-file-metadata-api.herokuapp.com/

## Deployment
Heroku is shown as a sample deployment because it's free and doesn't required a Procfile.

With the [Heroku CLI](https://devcenter.heroku.com/categories/command-line) installed,
```
heroku login -i
heroku create <app name>
heroku git:remote -a <app name>
git push heroku main
```

## Sample Requests
### Upload a file
#### Request
(upload a file using the web interface)
#### Response
```json
{
    "name": "Christopher_Ehrlich_Resume.pdf",
    "type": "application/pdf",
    "size": 45875
}
```
