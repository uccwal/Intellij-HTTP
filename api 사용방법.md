# GET localhost:8080/magic-api/employees

# POST localhost:8080/magic-api/employees
Content-Type: application/json

{
  "firstName": "dddeefess",
  "lastName": "ray",
  "email": "sfsf@code.com"
}

# PUT localhost:8080/magic-api/employees/4
Content-Type: application/json

{
  "firstName": "dddeefe",
  "lastName": "ray",
  "email": "sfsf@code.com"
}

# DELETE localhost:8080/magic-api/employees/4


# GET localhost:8080/magic-api/members
Authorization: Basic john test123
사용자인증 : Basic 아이디 패스워드