# Conduit API Testing Project

## 📌 Project Overview

This project contains API testing for the Conduit application (RealWorld example app).
The goal was to validate core functionality of the API including authentication, user management, and request validation.

## 🧪 Scope of Testing

The following areas were covered:

* User authentication (sign in)
* Negative authentication scenarios
* Input validation
* API response status verification

## ✅ Test Cases

Test cases are documented in the `/test-cases` folder.

Examples include:

* Successful sign in
* Sign in with invalid credentials
* Empty email/password validation
* Error handling validation

## ⚙️ Tools & Technologies

* Postman
* REST API
* JSON
* (optional) Newman

## 📂 Project Structure

* `collections/` — Postman collections
* `test-cases/` — documented test scenarios

## ▶️ How to Run

1. Import collection into Postman
2. Import environment
3. Set required variables (e.g. baseUrl)
4. Run collection manually or via Collection Runner

## 🚀 (Optional) Run via Newman

```bash
newman run collections/conduit.postman_collection.json -e environments/conduit_env.json
```

## 🎯 Key Achievements

* Designed structured API test scenarios
* Covered positive and negative test cases
* Validated API responses and status codes
* Organized test artifacts for easy reuse

## 📎 Notes

This project demonstrates API testing skills and can be extended with automated CI/CD integration.
