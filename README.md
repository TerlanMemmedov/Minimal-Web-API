# Web-API
- working
- Nothing for now

- Look for Just two sections:
  - LaunchSetteings.json => Removed both "launchUrl": "swagger" lines
  - Program.cs => Our whole work is inside here. We put our model, context, and all HttpRequests (Get, Post, Put) in this part. 
  - The program don't use any Sql type, just inside the program With InMemory Dependency Injection (temporary memory)
  - And you can control work with Postman program => body > raw > json :
                                                                - {
                                                                  - "name": "Run",
                                                                  - "isComplete": true
                                                                - } 
