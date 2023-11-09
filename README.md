# Travel Planner Web App 🌍

Welcome to the Travel Planner web app, a tool for organizing your travel itineraries, expenses, and more! ✈️🏖️

## Features
- 📅 Plan and organize your trip itineraries.
- 💰 Keep track of your travel expenses.
- 🏞️ Manage your destinations and activities.
- 🔍 Search and filter your data easily.

## Endpoints
- **Itinerary**:
  - `POST /itineraries`: Create a new itinerary activity for a destination.
  - `GET /itineraries/:destination_id`: Get all itinerary activities for a specific destination.
  - `PUT /itineraries/:itinerary_id`: Update a specific itinerary activity by ID.
  - `DELETE /itineraries/:itinerary_id`: Delete a specific itinerary activity by ID.

- **Expense**:
  - `POST /expenses`: Create a new expense for a destination.
  - `GET /expenses/:destination_id`: Get all expenses for a specific destination.
  - `PUT /expenses/:expense_id`: Update a specific expense by ID.
  - `DELETE /expenses/:expense_id`: Delete a specific expense by ID.

- **Destination**:
  - `POST /destinations`: Create a new destination.
  - `GET /destinations`: Get all destinations.
  - `PUT /destinations/:destination_id`: Update a specific destination by ID.
  - `DELETE /destinations/:destination_id`: Delete a specific destination by ID.

## Getting Started
1. Clone the repository.
2. Set up your backend using Flask.
3. Set up your frontend using React.
4. Run the development server.
5. Start planning your travels!

## Technologies Used
- Flask (Python)
- React (JavaScript)
- Ant Design (UI Framework)
- Axios (HTTP Requests)
- SQLAlchemy (Database)

## License
This project is licensed under the MIT License.

Enjoy your travel planning adventure! 🌴✨
