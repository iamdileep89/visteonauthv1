# visteonauthv1


Visteonauthv1 – Authenticate Microservice

# This service is to authenticate the user and send back the JWT token


curl --location --request POST 'http://localhost:3000/v1/api/visteon/auth/login' \
--header 'Content-Type: application/json' \
--data-raw '{
    "email": "dileep@123.com",
    "password": "dileep"
}'
