# Harry Potter API (OpenAPI & Swagger UI)

This repository contains the OpenAPI specification (version 3.0) and Swagger UI documentation for a RESTful Harry Potter API.  This API provides access to information about books, characters, houses, and spells from the Harry Potter universe.

**Visit the live version [here](https://vlaurencena.github.io/harry-potter-openapi-swagger-ui/).**

## API Description

The Harry Potter API offers endpoints for retrieving lists of entities (books, characters, houses, spells), as well as endpoints for retrieving random items.  It supports filtering and pagination through query parameters, and it's designed to be easily translated into multiple languages.

## OpenAPI Specification

The OpenAPI Document for the API is located in the `openapi.yaml` file.  This file defines all available endpoints, request/response formats, data models, and other details necessary for interacting with the API.

## Swagger UI

This repository includes Swagger UI, a tool that renders the OpenAPI specification into interactive documentation.  

### Running Swagger UI Locally

1. Clone this repository:
```bash
git clone https://github.com/[your-username]/harry-potter-openapi-swagger-ui.git
```
2. Open the `index.html` file in your web browser.  This should display the Swagger UI interface, loaded with the OpenAPI specification.
