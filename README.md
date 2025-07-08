# Smart Meal Generator

This project is an n8n workflow that:
- Uses a Webhook to receive user meal preferences
- Calls Gemini AI to create custom recipes
- Updates a Google Sheet with the recipe
- Sends the recipe by email
- Tested using Postman

## How to test

1. Import `n8n-workflow.json` into n8n.
2. Import `postman-collection.json` into Postman.
3. Use Postman to send requests to your webhook URL.

