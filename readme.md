# Social API Bruno
Created by Daniel Kravec, on Feb 7, 2024

## Description
This is a bruno project to test Interact's api. Bruno is a postman/insomnia alternative. Created this to test my api without building an entire frontend.


## How to run
1. Clone the project
2. Install bruno app from [usebruno.com](https://www.usebruno.com/downloads)
3. Edit ./collection.bru

    1. replace tokens with your interact tokens
    2. you can find your tokens at https://interact.novapro.net/?settings, and sroll down to Developer Settings
4. Open project inside bruno app
5. Change "http://localhost:5002/" with "https://interact-api.novapro.net/" if you are using the production api
6. Press run on the route you want. 


## Version History
### 1.0 (1.2024.02.07)
- Initial release
- Added badges route
- added readme

### 1.0.1 (1.2024.07.24) 
- added follow routes
- added auth userlogin route
- ()shouldve been 1.0, b2

### 1.0 (3.2024.11.10) 
- Added article routes (for future release)
- Added feed route 
- Added notifications, preferences, subscriptions routes for 1.7
- Added getpost route
- Added users/update, get, getUpdate routes