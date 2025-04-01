
# 📦 Product Management API

![Product Management API Banner](https://img.shields.io/badge/Product%20Management%20API-v2.0-blueviolet?style=for-the-badge&logo=go)  
![Go](https://img.shields.io/badge/Go-1.22+-00ADD8?style=flat-square&logo=go)  
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## Introduction

This is a Go-based Product Management API that provides functionality for managing products in an inventory system. Version 2.0 introduces rate limiting to prevent excessive API requests. It supports the following operations:

- Get all products
- Get product by ID
- Add a new product
- Update product details
- Delete a product

## New Features in Version 2.0

- **Rate Limiting**: This version includes rate limiting to ensure fair usage of the API. Requests will be limited to a specified number per minute to prevent overloading the system.

## How to Use

### Steps to Run the Project:

1. **Install Go**:
   Make sure you have Go installed on your machine. You can download it from [here](https://golang.org/dl/).

2. **Download the Project**:
   Clone the project to your local machine using Git:
   ```bash
   git clone <repository-link>
   ```

3. **Add Required Packages**:
   After downloading the project, navigate to the project folder, then run the following command to add the required packages:
   ```bash
   go mod tidy
   ```

4. **Run the Project**:
   To run the application, use the following command in the same folder:
   ```bash
   go run main.go
   ```

5. **Access the API**:
   The application will start listening on port 8080. You can access the API via:
   ```bash
   http://localhost:8080/api/products
   ```

## API Endpoints
(You can add the rest of the API details here as previously explained)

I’ve updated the README to include steps for installing Go, adding the necessary packages, and running the project.
