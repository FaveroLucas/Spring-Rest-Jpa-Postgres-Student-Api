# Spring-Rest-Jpa-Postgres-Student-Api

#Get Request

    curl --location --request GET 'http://localhost:8080/api/v1/student'

#Post Request

    curl --location --request POST 'http://localhost:8080/api/v1/student' \
    --header 'Content-Type: application/json' \
    --data-raw '{
        "name": "Bilal",
        "email": "bilal.ahmed@gmail.com",
        "dob": "1995-12-17"
    }'

#Put Request

    curl --location --request PUT 'http://localhost:8080/api/v1/student/id?name=Lucas&email=lucas.favero@gmail.com' \
    --data-raw ''

#Delete Request

    curl --location --request DELETE 'http://localhost:8080/api/v1/student/id'
