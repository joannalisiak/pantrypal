# PantryPal

PantryPal is a platform that helps you match ingredients you have at home with a vast recipe base. This project is divided into two separate GitHub repositories: one for the API built with Rails and one for the frontend built with Next.js. Each part is deployed separately to ensure scalability and maintainability.

## Repositories

- **API (Rails)**: [pantrypal-backend](https://github.com/joannalisiak/pantrypal-backend)
- **Frontend (Next.js)**: [pantrypal-frontend](https://github.com/joannalisiak/pantrypal-frontend)

## Deployment

- **API**: Deployed on Fly.io - https://pantrypal-api.fly.dev/api/v1/recipes
- **Frontend**: Deployed on Vercel - https://pantrypal-kappa.vercel.app/

## User Stories

### User Story 1: Search for Recipes Based on Available Ingredients

**As a** user \
**I want to** search for recipes based on the ingredients I have at home,\
**So that** I can easily find dishes I can prepare without needing to get additional ingredients.

### User Story 2: View Detailed Recipe Information

**As a** user,\
**I want to** view detailed information about a recipe,\
**So that** I can understand the ingredients, preparation time, cooking instructions (behind paywall), and other relevant details.

## Why Decoupled Architecture?

1. **Scalability**: Each part can be scaled independently based on the load and requirements.
2. **Flexibility**: Allows for independent development and deployment cycles.
3. **Maintainability**: Easier to manage and update each part without affecting the other.
4. **Technology Agnostic**: Enables the use of different technologies best suited for backend and frontend.

For more detailed information about each part of the project, please refer to the respective repository's README.
