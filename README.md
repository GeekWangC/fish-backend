# Todo Backend API

This is the backend API service for the Todo application, built with Node.js, Express, and PostgreSQL.

## Project Structure

```
backend/
├── src/
│   ├── config/         # Configuration files
│   ├── controllers/    # Route controllers
│   ├── middleware/     # Custom middleware
│   ├── models/         # Database models
│   ├── routes/         # API routes
│   ├── services/       # Business logic
│   ├── utils/          # Utility functions
│   └── app.js          # Express application setup
├── tests/              # Test files
├── .env.example        # Example environment variables
├── .gitignore         # Git ignore file
├── package.json       # Project dependencies
└── README.md          # Project documentation
```

## Prerequisites

- Node.js (v14 or higher)
- PostgreSQL (v14 or higher)
- npm or yarn

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Create a `.env` file based on `.env.example`:
   ```bash
   cp .env.example .env
   ```

4. Update the `.env` file with your database credentials and other configuration

5. Start the development server:
   ```bash
   npm run dev
   ```

## Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm test` - Run tests
- `npm run lint` - Run linter
- `npm run migrate` - Run database migrations

## API Documentation

The API documentation is available at `/api/docs` when running the server.

## Environment Variables

Required environment variables:

- `NODE_ENV` - Environment (development/production)
- `PORT` - Server port (default: 3000)
- `DB_HOST` - Database host
- `DB_PORT` - Database port
- `DB_NAME` - Database name
- `DB_USER` - Database user
- `DB_PASSWORD` - Database password
- `JWT_SECRET` - Secret for JWT token generation

## Contributing

1. Create a feature branch
2. Commit your changes
3. Push to the branch
4. Create a Pull Request

## License

This project is licensed under the MIT License. 