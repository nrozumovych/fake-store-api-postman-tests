# Fake Store API — Postman Test Collection

This repository contains an end-to-end API testing workflow built using Postman and the Fake Store API. It demonstrates how a QA engineer can design, execute, and validate API tests using dynamic variables, JavaScript-based test scripts, and environment settings.

## Overview

This collection simulates a user interaction flow with an e-commerce system via API:

- User login with environment-managed credentials
- Fetching product listings and selecting one dynamically
- Creating a cart for a specific user and adding the selected product
- Retrieving the user's cart and validating its content

## Features

- Dynamic environment variables (`token`, `userId`, `productId`, etc.)
- Pre-request and test scripts written in JavaScript
- Response validation for status codes, data formats, and business logic
- Random product selection from product list
- Basic date format validation
- Reusable test flow that supports Collection Runner

## Folder Structure
```bash
├── collections/
│ └── FakeStoreAPI.postman_collection.json
├── environment/
│ └── FakeStoreAPI_environment.postman_environment.json
└── README.md
```

## How to Use

1. Import the collection and environment files into Postman.
2. Set environment variables for login credentials and base URL.
3. Run requests sequentially or use the Collection Runner.
4. Review validation logic and test assertions for each request.

## Disclaimer

This collection is a demo project created for educational purposes.  
It uses a public API (https://fakestoreapi.com) and does not contain any real or confidential data.
