# Xilium

Welcome to the Xilium recruitment assessment.

## Run the development server

Run `npm install` to fetch packages then run `npm run dev` to start the development server.

## Task 1 - Display Products

This repository includes an OpenAPI specification that documents an external API. Note that we'll working with product data from the corporation with ID `1950`. Also note that the API is using some simple authentication, api key to be found in the spec as well. Your first challenge is to:

1. Review the API documentation to understand the available endpoints
2. Implement a solution to fetch product data for a given category from the API
3. Display the products in a table with appropriate UI handling for loading and error states

**Note**: We've included `@tanstack/react-query` as a dependency which may be helpful for managing API requests and data fetching, though you're welcome to use any approach you prefer.

> Chakra UI v3 is also available as a dependency, as it's the primary UI library in the Xilium codebase. Feel free to leverage its components for your implementation.

## Task 2 - Filter & Search

Enhance your product table by adding client-side filtering and search functionality:

- Implement search capabilities (e.g., searching products by name)
- Add relevant filters to help users quickly find specific products
- Ensure the filtering/search experience is intuitive and performant

This task is intentionally open-ended to allow you to demonstrate your approach to UI/UX problems and state management.
