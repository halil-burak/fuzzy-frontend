# Product Fuzzy App Frontend

This is the frontend part of the Product Fuzzy App, a simple web application for displaying and searching products. The application is built using HTML, JavaScript, and React, and it communicates with a backend API.

## Features

- Display a list of products
- Search for products by name
- View product details

## Prerequisites

- Node.js and npm installed

## Getting Started

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/fuzzy-frontend.git
   cd fuzzy-frontend

2. Install dependencies:
    ```sh
    npm install

3. Start the development server:
    ```sh
    npm start

The application will be available at http://localhost:3000.

## API Endpoints
- **GET /api/products: Fetch all products**
- **GET /api/products/search?term={query}: Search for products by name**
- **GET /api/products/{id}: Fetch product details by ID**

## Project Structure

```
fuzzy-frontend/
├── public/
│   ├── index.html
│   ├── product-detail.html
├── src/
├── .env
├── package.json
```

### Usage
- Open the application in your browser.
- Use the search bar to search for products by name.
- Click on a product to view its details.
