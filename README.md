Documentation:

1.	“npm init” command in terminal, to create package.json file in project folder.

2.	“npm install express winston” command to install express.js framework and Winston logger.

3.	Created “server.js” file, with all 4 endpoints accept two query parameters: num1 and num2

•	/add: Addition
•	/subtract: Subtraction
•	/multiply: Multiplication
•	/divide: Division

4.	Run the microservice by using “node server.js” command.
5.	API endpoint examples

Addition - http://localhost:3000/add?num1=10&num2=15
Response:
{
    "result": 25
}

Addition - http://localhost:3000/add?num1=10
Response:
{
    "error": "Both numbers are required"
}


Subtraction - http://localhost:3000/subtract?num1=10&num2=6
Response:
{
    "result": 4
}

Multiplication - http://localhost:3000/multiply?num1=10&num2=6
Response:
{
    "result": 60
}

Division - http://localhost:3000/divide?num1=10&num2=6
Response:
{
    "result": 1.6666666666666667
}

Division - http://localhost:3000/divide?num1=10&num2=0
Response:
{
    "error": "Division by zero is not allowed"
}


Exponentiation - http://localhost:3000/power?num1=10&num2=6
Response:
{
    "result": 1000000
}


Square Root - http://localhost:3000/sqrt?num1=64
Response:
{
    "result": 8
}


Modulo - http://localhost:3000/modulo?num1=10&num2=6
Response:
{
    "result": 4
}

6.	Verify logs in logs directory

Comibined.log: contains all logged messaged
 
Error.log: contains all error messages

 
