# ITTraining_Student_Rest_API_Newman
## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run ITTrainingPractice2.postman_collection.json -e ITTrainingPractice2.postman_environment.json  
```
- Run Command for Report: 
```console 
newman run ITTrainingPractice2.postman_collection.json -e ITTrainingPractice2.postman_environment.json -r cli,htmlextra -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/23999799/2s93eZzCYR

## Test case list:
1. ### Create Student
	> Create Data Sets Using the Dynamic Random Variables.

2. ### Verify Crated Student Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Middle Name
 	3. > Last Name
 	4. > Date of Birth

3. ### Update Student
	> In the test case you need to validate the following field values:
 	1. > Only Message
4. ### Verify Verify Updated Student Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Middle Name
	3. > Last Name
 	4. > Date of Birth

5. ### Create Technical skills Create Student Address
	> In the test case you need to validate the following field values:
	1. > Only Message

6. ### Create a Student Address
	> In the test case you need to validate the following field values:
	1. > Only Message

7. ### Get the Student's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
	2. > Middle Name
	3. > Last Name
	4. > Date of Birth


8. ### Delete Specific Student
	> In the test case you need to validate the following field values:
	1. > Only Message

## Newman Report Summary:
![Newman Report](https://github.com/joy8cse/ITTrainingStudentDetails/assets/58203167/47f2bf06-ef36-43aa-8e21-c8f8efd256a6)

![Newman Report Summary](https://user-images.githubusercontent.com/70250199/232209794-f84c539b-e3cf-4e80-ab0e-9d6d59b1a339.png)
