# tiktok-tech-immersion-2023-Assignment
Tiktok Tech Immersion Backend Server Assignment

Instant Messaging System Backend
This project assignemnt is focused on implementing a backend instant messaging system using Golang based on the Demo template file provided. 
The project does not include a front-end or authentication layer, focusing purely on the messaging service function itself.

Table of Contents
Requirements
Getting Started
Running the Project
Testing
Requirements
Before starting, ensure you have the following installed:

Golang
MySQL or Redis
Getting Started
After ensuring that Golang and your chosen database (MySQL or Redis) are installed, clone this repository to your local machine.

bash
Copy code
git clone https://github.com/your-repo/instant-messaging-system.git
cd instant-messaging-system
Running the Project
Once you have cloned the repository and navigated into the directory, you can run the project using the following command:

bash
Copy code
go run main.go
Please ensure the database is running before you start the service. Depending on the database you have chosen, you may need to adjust the connection string in the configuration file.

Testing
We have implemented a basic set of tests that can be run with:

bash
Copy code
go test ./...
These tests ensure that the system is capable of handling a large number of users and messages. The system should be able to support more than 20 concurrent users in testing.

Troubleshooting
If you run into issues while setting up or running the project, please open an issue in the GitHub repository. We are happy to assist with any problems you may have.

License
MIT
