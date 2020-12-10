    A Golang Gin API For Saving Videos
    
    Start:
    $ go mod tody
    $ go run server.go
    
    Authorization Type: 
    Basic Auth
    
    Credentials :
    username: admin
    password: admin
    
    Add Videos:
    $ POST localhost:8080/api/videos 
    
    Format:
    JSON
    
    Example:
    {
        "title": "Cool classic",
        "description": "classics",
        "url": "https://www.youtube.com/embed/DB5rHnmsag8",
        "author": {
            "firstname": "Mozart",
            "lastname": "Classic",
            "age": 20,
            "email": "test@gmail.com"
        }
    }
    
    Get Videos:
    $ GET http://localhost:8080/view/videos

    
