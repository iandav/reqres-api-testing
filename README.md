# reqres-api-testing

## Introduction
This is a practical personal project to practice the concepts of API Testing. The API is called "Reqres" and you can access here https://reqres.in/ to view its functionalities and expected responses from the server.

## Scope
The scope of the project includes testing the following functionalities of the Reqres API:
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
Creating Test Scenarios and Test Cases for the different features listed before, including different testing design techniques such as:
<ul>
  <li>Equivalence Class Partition</li>
  <li>Decision Tables</li>
  <li>Positive/Negative Testing</li>
  <li>Basic Security Testing</li>
  <li>Error Guessing</li>
</ul>

(Considering that the application is in a stable version, Smoke Testing has been omitted in this project.)
<br/>Almost every request in the Test Case must contain the following actions:
1) Verify expected HTTP status code.
2) Verify the response payload.
3) Verify important headers.
4) Verify acceptable response time.

## Run tests using newman
<code>npm install newman</code>


## Test Results

