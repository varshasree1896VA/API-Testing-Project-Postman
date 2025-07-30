# API Testing Practice Project

This is a beginner-friendly project for practicing API testing using **Postman**. It covers 14 public APIs provided by [Automation Exercise](https://automationexercise.com/api) for various HTTP methods like GET, POST, PUT, and DELETE.

## 🔧 Tools Used

- Postman  
- JSON  
- Git & GitHub (to version and share the project)

## ✅ Tested APIs

| #  | API Description                          | Method |
|----|----------------------------------------|--------|
| 1  | Get All Products List                   | GET    |
| 2  | POST to All Products List               | POST   |
| 3  | Get All Brands List                     | GET    |
| 4  | PUT to All Brands List                  | PUT    |
| 5  | Search Product                         | POST   |
| 6  | Search Product (no parameter)          | POST   |
| 7  | Verify Login (valid)                    | POST   |
| 8  | Verify Login (missing email)            | POST   |
| 9  | Verify Login (delete method)            | DELETE |
| 10 | Verify Login (invalid credentials)      | POST   |
| 11 | Create/Register User Account            | POST   |
| 12 | Delete User Account                    | DELETE |
| 13 | Update User Account                    | PUT    |
| 14 | Get User Account by Email              | GET    |

## 📌 Features Practiced

- Sending GET, POST, PUT, DELETE requests  
- Adding headers, parameters, and body content  
- Validating status codes: 200, 201, 400, 404  
- Debugging common API issues like:  
  - Missing parameters  
  - Duplicate email registration  
  - Handling 404 Not Found and 400 Bad Request  

## 📂 How to Use

1. Open **Postman**  
2. Manually create or import each API request  
3. Set required parameters, headers, and body where needed  
4. Observe response status, time, and JSON body  
5. Optionally, organize all 14 requests into a Postman **Collection**  

## 📝 Sample JSON Response

```json
{
  "responseCode": 201,
  "message": "User created!"
}
```
## 💡 Learning Outcome

- Understanding API basics: endpoints, methods, requests/responses

- Confidence in using Postman for getting practical experience

- Practical Learning experience of how to test API's

## 📁 Project Folder Structure (example)

api-testing-practice-project/
├── README.md
└── postman_collection.json

## 📎 Notes

- These APIs are publicly available only for practice/testing purposes.
- No sensitive data or real accounts are involved.
