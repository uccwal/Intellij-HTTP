# GET 요청

### GET localhost:8080/magic-api/employees

# POST 요청
### POST localhost:8080/magic-api/employees
Content-Type: application/json

{
  "firstName": "dddeefess",
  "lastName": "ray",
  "email": "sfsf@code.com"
}

# PUT 요청
### localhost:8080/magic-api/employees/4
Content-Type: application/json

{
  "firstName": "dddeefe",
  "lastName": "ray",
  "email": "sfsf@code.com"
}

# DELETE 요청
### localhost:8080/magic-api/employees/4

4 -> PK

# 사용자 인증 있을시
### localhost:8080/magic-api/members
Authorization: Basic john test123
사용자인증 : Basic 아이디 패스워드
