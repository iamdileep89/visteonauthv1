# visteonauthv1


Visteonauthv1 – Authenticate Microservice

# This service is to authenticate the user and send back the JWT token


curl --location --request POST 'http://localhost:3000/v1/api/visteon/auth/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "email": "dileep@123.com",
    "password": "dileep"
}'
![image](https://user-images.githubusercontent.com/98578797/151507709-af0d1c65-0848-4aea-895e-3a39f52e2983.png)
