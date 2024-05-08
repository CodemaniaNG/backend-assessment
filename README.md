# Backend Engineer Assessment

Build a RESTful API using Node.js, Express, TypeScript, and a SQL database (preferrably PostgreSQL).

## Task
You are tasked with building an API for a logistics company that provides the following standard features:

- **Authentication**: Implement user authentication functionality to allow users to securely access the API endpoints.

- **Package Sending**: Implement endpoints that allow users to submit packages for delivery. Each package should include the following information:
  - Package name
  - Status (candidates are free to assign the type of values)
  - Pick-up date (the date the user picks up the package)
  - Timestamp

- **Package Tracking**: Implement endpoints that allow users to track their packages. Users should be able to retrieve real-time updates on the status of their packages.

- **Automated Package Updates**: Implement automated updates on the status of the package. For the sake of this assessment, the system should continuously update the status of the package at short intervals (e.g., every 2 minutes) until it reaches a state that indicates the user's package is available for pickup.

note: seed the database for user data and packages to make the api ready for immediate testing (You can utilise a tool like mockaroo to generate dummy data).


## Evaluation Criteria
- **Database Design**: Structure, relationships, and indexing strategy. (You have been given base assumptions about the database structure you are too figure out the missing pieces)

- **API Design & Implementation**: RESTful practices, efficiency of the code.

- **API Documentation**: Ability to document api contract.

- **Query Efficacy**: Ability to optimize the provided SQL query.

- **Code Quality**: Readability, maintainability, and use of TypeScript features.

- **Error Handling**: How robust the application is against unexpected situations or invalid input.

## Submission
1. The application should be dockerized
  
2.  The apis should be documented using postman.

3.  Code should be hosted on a git repository, Github preferably.

4.  The api should be hosted on a live server (https://render.com)

5.  Share with us through email the:
    - Repository

    - Hosted API URL

    - Postman Collection Public URL
