# Nutritional-Calculator-Web-App

Nutritional-Calculator-Web-App is a full-stack web application that analyzes food ingredients and recommends healthier alternatives using semantic data. It is built with Node.js and Next.js, and leverages a SPARQL-powered knowledge graph for accurate, real-time nutritional insights. The app is deployed on Vercel.

## Features

- Nutritional Analysis: Evaluate food items for calories, macronutrients, and dietary suitability.
- Smart Recommendations: Get healthier alternative ingredients based on nutritional data.
- Real-time Performance: Uses asynchronous operations and caching for a fast user experience.
- SPARQL Integration: Queries nutritional data from a semantic knowledge graph.
- Semantic Search: Understands and interprets ingredient inputs intelligently.

## Tech Stack

- Frontend: Next.js, Tailwind CSS
- Backend: Node.js, SPARQL endpoint
- Deployment: Vercel
- Data Layer: Nutritional knowledge graph via SPARQL

## Installation

```bash
git clone https://github.com/DeepanjayNandal/Nutritional-Calculator-Web-App.git
cd Nutritional-Calculator-Web-App
npm install
npm run dev
```

## Usage

- Enter an ingredient (e.g., "butter").
- View its nutritional profile.
- See alternative suggestions like "olive oil" with improved macros.

## Security

- No user data is stored.
- All queries are sanitized to prevent injection attacks.

## Future Improvements

- Add user accounts and dietary profiles.
- Expand to meal-based suggestions.
- Support barcode scanning for ingredients.
