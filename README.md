
## K6: For load testing

## Introduction
- K6 is a tool for testing the performance of APIs and web applications under load. It allows you to write tests in JavaScript and simulate traffic to help identify bottlenecks, measure response times, and test how the system performs under various load conditions.

## Installation
- Node.js (optional, for local execution of K6 scripts)
- K6
- Install any necessary dependencies - npm install
# Clone this repository to your local machine
git clone https://github.com/yourusername/k6-load-testing.git
 cd k6-load-testing
 

## Running the Tests
- k6 run scriptname.js
  
## different options like duration, virtual users
- k6 run --vus 50 --duration 30s load_test.js
  
## Analyzing Results
# Once a test completes, K6 will output the results in the terminal -
Request Duration: Time taken to handle requests.
Throughput: Requests per second.
Error Rate: Percentage of failed requests.
Response Time Distribution: The distribution of response times


