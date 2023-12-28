# Country Information Fetcher

This JavaScript code utilizes XMLHttpRequest to interact with the [Rest Countries API](https://restcountries.com/v3.1/all) to retrieve and process country information.

## Overview

The provided JavaScript snippet employs XMLHttpRequest to fetch data from the Rest Countries API endpoint and perform various operations on the retrieved country information.

- **XHR Object**: The code initializes an XMLHttpRequest object (`xhr`) and sends a GET request to the specified API endpoint.

- **Event Handling**: Upon the XHR object's `onload` event, the code processes the response data.
  - If the response status is 200 (OK), it parses the JSON response and performs the following actions:
    - Logs specific country details such as name, capital, and flag.
    - Calculates and logs the total population of all countries.
    - Filters and logs countries with a population of less than 200,000.
    - Filters and logs countries in the Asian region.
    - Filters and logs countries using US Dollars (USD) as currency.


## Usage

1. The code can be integrated into a JavaScript file within your project environment.
2. Ensure that the Rest Countries API endpoint remains accessible and functional for data retrieval.
3. Execute the code to observe the fetched country information and the performed operations as specified in the console.

