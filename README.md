### Flask application for GET POST rest api calls

#### How to run application?
#### Navigate to project root folder and execute following command
```sh app_run.sh```  Shell Script  will install all project dependencies and runs flask application. 
Navigate to following paths in browser for swagger documentation
```http://127.0.0.1:5000/swagger/```
Execute POST and GET requests to add numbers and retrieve sum
### To Run unit tests use following command
```pytest```


###To Run main code use following command
'''python src/main.py'''

### To Run application with POSTMAN
when you start application get returns 404, then add number using post method 
each post call will sum numbers by adding existing number.
POST call : ''' http://127.0.0.1:5000/total/10'''
GET call: '''http://127.0.0.1:5000/total'''