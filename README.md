# REST API Client Using Java

## CodTech Internship - Task 2

### Overview

This project demonstrates how to consume a public REST API using Java. The application sends an HTTP GET request to the GitHub API, retrieves user information, and displays the JSON response in the console.

### Objective

To understand and implement REST API communication in Java using built-in networking classes.

### Features

* Connects to a public REST API.
* Sends HTTP GET requests.
* Retrieves data from the server.
* Reads and displays JSON responses.
* Includes exception handling for reliable execution.

### Technologies Used

* Java
* HttpURLConnection
* URL
* BufferedReader
* InputStreamReader

### API Endpoint

https://api.github.com/users/octocat

### Project Structure

```text
RestApiClient.java
README.md
```

### How It Works

1. Creates a connection to the GitHub API.
2. Sends an HTTP GET request.
3. Receives the JSON response from the server.
4. Reads the response using BufferedReader.
5. Displays the response in the console.

### Sample Output

```json
{
  "login": "octocat",
  "id": 583231,
  "node_id": "...",
  "avatar_url": "...",
  "type": "User"
}
```

### Learning Outcomes

* Understanding REST API concepts.
* Working with HTTP requests and responses.
* Reading data from web services.
* Handling exceptions in Java applications.
* Processing JSON data from APIs.

### Author

Subhashini Cheeday

### Internship Program

CodTech IT Solutions Internship
