# API project featuring Django REST framework and MongoDB

**[Link to my live API](https://automatrixapi.pythonanywhere.com/)**

Welcome to another one of my backend projects. Here I have created a NoSQL web API with Django REST framework featuring full CRUD functionality and exhaustive integration testing. This API is built upon a document data model and is connected to document collections hosted on a MongoDB database cluster.

Visit the link above to view the browsable API which will enable you to explore all of the API's endpoints, HTTP methods and error messages.

## Endpoints
- /api/patterns 
    - **GET | POST**
- /api/patterns/:pattern_id 
    - **GET | PUT | DELETE**
- /api/users 
    - **GET | POST**
- /api/users/:user_id 
    - **GET | PUT | DELETE**
- /api/users/:username/patterns 
    - **GET**


## Key product features:
- Browsable front-end with responsive design elements.
- Based on an MVT design pattern.
- Variety of endpoints providing GET, POST, PUT and DELETE functionality.
- Extensive error handling with custom error messages for distinct concerns.
- Full integration testing using Django's test case class.
- Function-based views and class-based tests.
- Virtual environment for project dependencies.
- Multi-app project structure, in line with best practice.


## Screenshots
Making a GET request for all patterns by a specific user:
<br>
<img width="500" src="api_view3_iPad_Air.png">

Making a PUT request for a user:
<br>
<img width="500" src="api_view2_iPhone_SE.png">

Making a POST request:
<br>
<img width="500" src="api_view1_Surface_Pro_7.png">