# Cars Code Challenge

Requires Java 17

Instructions:

### Part 1: Debug and fix startup issues

### Part 2: Fix Reported Bugs

##### Bug 1: When submitting a valid request to create a car, it is returning a 400 response with a bunch of raw text
##### Bug 2: A car's make does not appear to be getting updated correctly on a valid request to the /api/cars/update endpoint
##### Bug 3: After submitting a valid request to the api/cars/delete endpoint, the car is still being returned in the GET /api/cars response

Example Create Car Payload: 
```json
{
  "make": "Audi",
  "model": "S4",
  "year": "2020",
  "vin": "AASDF90UA90JN309A2"
}
```

### Part 3: Refactor service class - Modernize the code

### Part 4: Refactor API contract to be more RESTful, where applicable

### Bonus: What else did you find?