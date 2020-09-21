# ECE444-F2020-Lab2
Devesh Nischal
This repo is a clone of
https://github.com/miguelgrinberg/flasky

Activity 1: ![Importing Flask](https://github.com/devesh-nischal/ECE444-F2020-Lab2/blob/master/Importing_Flask.JPG?raw=true)

Activity 2: ![Dynamic Routing example](https://github.com/devesh-nischal/ECE444-F2020-Lab2/blob/master/Dynamic_Routing.JPG?raw=true)

Activity 3:  
Flask uses contexts to make certain information available globally within the program. This is required to get that information to the view function. The reason contexts are used is to ensure that each thread has its own version of that object. Flask utilizes two contexts: the application context and the request context.  
The application context exposes two variables called "current_app" and "g". "current_app" holds the active application instance and "g" is an object that the application can use for temporary storage while running. "g" is reset with every request.  
The request context also exposes two variables called "request" and "session". "request" holds the contents of the HTTP request sent by the client. "session" holds a dictionary which is remembered between requests and can be used to store values.  
