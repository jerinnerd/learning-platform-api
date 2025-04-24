# learning-platform-api
A mock API for managing users, courses, and progress in an online learning platform
# Learning Platform API (Mock Project)

This is a mock RESTful API designed for an online course platform. It simulates user registration, course management, enrollment, and progress tracking.

## 🧪 API Features

- Register users
- List and create courses
- Enroll users in courses
- Track course progress

## 🛠️ Tools Used

- Postman (Mock Server + Collection)
- Swagger (OpenAPI Spec)
- GitHub

## 🔗 Live Mock Server

[Insert Postman mock server link here]

## 📂 Files Included

- `postman_collection.json`: Import this into Postman
- `openapi.yaml`: Swagger/OpenAPI documentation
- `product_spec.pdf`: High-level PM spec

## 👨‍💻 Sample API Call

```bash
curl -X POST https://mockserver-url.com/users \
  -H "Content-Type: application/json" \
  -d '{"name": "John Doe", "email": "john@example.com"}'
