# Weather API Postman Collection:

This repository contains a Postman collection for testing and interacting with the Weather API. 
It covers various endpoints for retrieving current weather, forecasts, historical data, and more, as well as error-handling scenarios.

### Features:
- Current Weather: Fetch real-time weather data for a specific location.
- Forecasts: Retrieve weather forecasts for multiple days, including hourly breakdowns.
- Historical Data: Access weather information for past dates.
- Error Handling: Test cases for invalid API keys, missing parameters, and exceeded rate limits.
- Search: Search locations by city, ZIP code, or latitude/longitude.
- Response Validation: Includes robust test scripts for data validation, schema checks, and performance monitoring.

# Setup Instructions:
### Prerequisites:
- Install Postman.
- Create an account on Weather API and obtain an API key.
### Importing the Collection:
1. Clone this repository:
   - https://github.com/HalaEzzatMahmoud/Weather-API.git
2. Open Postman.
3. Import the collection:
     - Go to File > Import.
     - Select the Weather API.postman_collection.json file from this repository.
# Test Scripts
### Validation:
1. Ensures all key fields are present and have the correct data types (e.g., temp_c is a number, condition.text is a string).
2. Performance: Checks that response time is under 2000ms.
3. Error Scenarios: Tests invalid inputs, missing API keys, and rate limits.

  
  
