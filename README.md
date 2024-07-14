USA Data API Test Suite
Overview
This project contains a comprehensive test suite for the USA Data API, developed using Postman. The test suite covers various endpoints and ensures the integrity and reliability of the data provided by the API. The primary focus is on validating the API's responses for different data metrics across the United States, including population, income, employment, and more.

Key Features
Comprehensive Coverage: Tests for a wide range of metrics including population, income, employment, and more, ensuring the API's robustness and accuracy.
Parameterization: Dynamic handling of API parameters to test various data drilldowns and measures efficiently.
Dynamic Data Extraction: Utilizing Postman's scripting capabilities to dynamically extract and validate data from API responses.
Schema Validation: Rigorous schema validation to ensure the API responses conform to the expected structure.
Error Handling: Comprehensive error handling to capture and report any anomalies or issues with the API responses.
Performance Checks: Automated checks for response time to ensure the API meets performance standards.
Collection Structure
The collection includes the following key requests:

Get Population by Nation: Validates the population data at a national level.
Get Population by State: Tests population data across different states.
Get Median Age by State: Verifies the median age data across states.
Get Median Household Income by State: Ensures the accuracy of household income data by state.
Get Employment by State: Checks employment data across various states.
Get Educational Attainment by State: Validates educational attainment data across states.
Get Poverty by State: Ensures the correctness of poverty data by state.
Get Housing Units by State: Verifies housing unit data across states.
Get Veterans by State: Checks data on veterans by state.
Get Businesses by State: Validates the number of businesses across states.
  Usage
Clone the Repository:
"git clone https://github.com/your-username/USA-Data-API-Test-Suite.git"
"cd USA-Data-API-Test-Suite"

Import the Collection to Postman:

Open Postman and click on the Import button.
Select the JSON file from the cloned repository.

Set Up Environment Variables:

Configure the necessary environment variables (baseUrl, drilldowns, measures) in Postman.

Run the Test Suite:
Select the collection and click on the Run button to execute the tests.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the project's coding standards and includes appropriate tests.
