# Documentation
# First MicroTask
#### It is an API that does basic querying operations.

### Repo Link
    https://github.com/ayushman007/Micro-task-1

### Deta Link
    https://ylowq4.deta.dev/

### Clone the git repository
    git clone  https://github.com/ayushman007/Micro-task-1

### Navigation
    cd Micro-task-1 

### Installation
    npm i

### Runserver
    npm start


### Endpoints
Make a GET Request : To get details of all users or specific user.

    /users/
    /users/${id}

Make a POST Request : Enter firstname, lastname and age in JSON format to create a user.

    /users/

Make a PATCH Request : Enter parameters that needs to be updated in JSON format of a specific user.
     
    /users/${id}

Make a DELETE Request : To delete details of a specific user.

    /users/${id}     




# Second MicroTask
#### Microservice which performs three tasks : ErrorHandling, Visitor counter and Authentication

#### Repo Link
    https://github.com/ayushman007/MicroTask-2
    
#### Clone the git repository
    git clone https://github.com/ayushman007/MicroTask-2

#### Navigation
    cd MicroTask-2
    cd Authentication or cd ErrorHandling or cd ViewCounter

#### Installation
    npm i

#### Runserver
    npm start

## API Reference

### ErrorHandling

#### Handle Errors using custom middlewares inculing CORS error and various server errors. 
GET Request:

    /error

### Authentication
#### Handles operations such as signup and login.
#### Sign-up

POST Request:

    /signup


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| body | email | Required|
| body | password | Required|


#### Log In(Returns token)

POST Request:

    /login


| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| body | email | Required|
| body | password | Required|

### Visitor counter

#### It counts the number of visits in a particular endpoint.

GET Request:

    /counter

# Third MicroTask
####  The user's latitude and longitude from the html geolocation service is used used to develop a location microservice that can use them and provide the address.It also uses address to get latitude and longitude.

#### Repo Link
    https://github.com/ayushman007/MicroTask3

#### Deta Link
    https://ngco2w.deta.dev


### API Refernce

#### Clone the git repository
    git clone  https://github.com/ayushman007/MicroTask3

#### Navigation
    cd MicroTask3  

#### Installation
    npm i
    npm start


#### Endpoints
GET Request:

    /
 
## Author
- [@ayushman007](https://github.com/ayushman007)

