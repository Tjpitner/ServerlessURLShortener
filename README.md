# Serverless URL Shortener

## Overview
This project is a serverless URL shortener built using AWS Lambda, API Gateway, and DynamoDB. It allows users to create shortened URLs and redirects to the original URLs.

## Architecture
- **Front-End**: None (API only).
- **Back-End**: AWS Lambda functions for URL creation and redirection.
- **Database**: Amazon DynamoDB to store URLs.

## Setup

### Prerequisites
- AWS Account
- Node.js and npm (for local development)

### Steps

1. **Create DynamoDB Table**:
    - Go to AWS Management Console.
    - Create a table named `UrlTable` with `id` as the primary key.

2. **Create Lambda Functions**:
    - Create `createShortUrl` and `getOriginalUrl` Lambda functions with provided code.

3. **Set Up API Gateway**:
    - Create REST API with endpoints for shortening URLs and redirection.

4. **Deploy the API**:
    - Deploy the API and note the Invoke URL.

5. **Test the Application**:
    - Use Postman or cURL to test the API.

## License
[MIT](LICENSE)

