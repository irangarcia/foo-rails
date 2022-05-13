# MVC Pattern

`GET /about HTTP/1.1` <br/>
`Host: 127.0.01`

GET for `"/about"`

## Routes
_tldr_: the routes on your rails app are just saying: here is your URL, lets give to the controller to decide how to process that; 

Matchers for the URL that is requested

GET for `"/about"`

I see you requested `"/about"`, we'll give that to the `AboutControler` to handle.


## Models
Database wrapper

User
* query for records (e.g: let's find all users who logged in in the last 24hrs)
* wrap individual records (e.g: validations, username must be at least 3 characters long)

## Views

Your response body content:
* `.html`
* `.css`
* `.pdf`
* `.xml`

## Controllers 
_tldr_: your controller can say: you tried to create a new user account but your password wasn't long enough, so we will give you an error back, but if is long enough we can redirect you to the home page (e.g: decides where the things go)

Decide how to process a request and define a response.

