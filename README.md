## FreeCodeCamp Timestamp Microservice
By M MUKIT

This repository is for the freecodecamp api project called "Timestamp Microservice". More details: https://www.freecodecamp.com/challenges/timestamp-microservice

### User Stories

1. User can pass a string as a parameter, and this app will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016).

2. If it does, it returns both the Unix timestamp and the natural language form of that date.

3. If it does not contain a date or Unix timestamp, it returns null for those properties.

### Example Input 

```
https://freecodecamp-timestamp-microservice-imukit007.c9users.io/December%2015,%202015
https://freecodecamp-timestamp-microservice-imukit007.c9users.io/1450137600
```

### Example Output

```
{ 
    "unix": 1450137600, 
    "natural": "December 15, 2015" 
}

Or

{ 
    "unix": null, 
    "natural": null 
}
```

### Live Preview

```
https://freecodecamp-timestamp-microservice-imukit007.c9users.io/
```
