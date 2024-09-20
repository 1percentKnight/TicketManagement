# Ticket Management System

## Setup Instructions

1. Clone the repository:

git clone <repository-url> cd ticket-management-system


2. Install dependencies:
npm install


3. Create a `.env` file and add your MongoDB connection string:
MONGO_URI=mongodb://localhost:27017/ticketManagement

4. Start the server:
npm run dev


5. API Endpoints:
- **POST /api/tickets**: Create a new ticket.
- **GET /api/tickets**: Retrieve all tickets.
- **GET /api/tickets/:id**: Retrieve a ticket by ID.
- **PUT /api/tickets/:id**: Update a ticket by ID.
- **DELETE /api/tickets/:id**: Delete a ticket by ID.