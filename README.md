# reqres-api-testing

# Overview
<ul>
  <li><a href="#Introduction">Introduction</a></li>
  <li><a href="#Scope">Scope</a></li>
  <li><a href="">Test Strategy</a></li>
  <li><a href="">Run tests/collections on your computer using newman</a></li>
  <li><a href="">Test Results</a></li>
</ul>

## Introduction
This is a practical personal project to practice basic concepts of API Testing. The API is called "Reqres" and you can access [here](https://reqres.in/) to view its functionalities and expected responses from the server. The main tools/technologies used are Postman, Newman, JavaScript and Chai BDD.

## Scope
The scope of the project includes testing the following functionalities of the API:
<ul>
  <li>Login</li>
  <li>Register</li>
  <li>Create user data</li>
  <li>Update user data</li>
  <li>Delete user data</li>
  <li>Get a list of users</li>
  <li>Get a single user</li>
  <li>Basic Security and Authentication</li>
</ul>

## Test Strategy
Creating Test Scenarios and Test Cases for the different features listed before, including different test case design techniques such as:
<ul>
  <li>Equivalence Class Partition</li>
  <li>Decision Tables</li>
  <li>Positive/Negative Testing</li>
  <li>Basic Security Testing</li>
  <li>Error Guessing</li>
</ul>

Almost every request in the Test Cases must contain the following actions:
<ol>
  <li>Verify expected HTTP status code.</li>
  <li>Verify the response payload.</li>
  <li>Verify important headers (optional).</li>
  <li>Verify acceptable response time.</li>
</ol>

(Considering that the application is in a stable version, Smoke Testing has been omitted.)

## Run tests/collections on your computer using newman
1. Install [Nodejs](https://nodejs.org/)
2. Install newman with npm: <code>npm install -g newman</code>
3. Install newman html reporter: <code>npm install -g newman-reporter-html</code>
4. Clone this repository: <code>git clone https://github.com/iandav/reqres-api-testing/</code>
5. Run .json collections: <code>newman run collection_name.json -r html</code>
6. View test results created in the project folder as an html file.

## Test Results
|  | Total | Failed |
| --- | --- | --- |
| Iterations | 1 | 0 |
| Requests | 15 | 0 |
| Prerequest Scripts | 2 | 0 |
| Test Scripts | 15 | 0 |
| Assertions | 44 | 14 |

| Total Failures: |
| --- |
| 14 |


