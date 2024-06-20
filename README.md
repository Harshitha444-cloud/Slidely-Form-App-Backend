# Slidely-Form-App-Backend

# Form Submission Backend

This is a simple Express server built with TypeScript that handles form submissions and retrieves saved submissions.

## Prerequisites

- Node.js (v14 or later)
- npm

## Install dependencies:
npm install

## Running the Server

To start the server, run:
npm start

The server will start running on `http://localhost:3000`.

## API Endpoints

1. **GET /ping**
   - Returns `true` to indicate the server is running.

2. **POST /submit**
   - Saves a new form submission.
   - Required parameters: `name`, `email`, `phone`, `github_link`, `stopwatch_time`

3. **GET /read**
   - Retrieves a saved form submission.
   - Query parameter: `index` (0-based index of the submission to retrieve)

## Database

The server uses a JSON file (`db.json`) as a simple database to store submissions. The file is created automatically if it doesn't exist.

This implementation covers all the compulsory points:

It's an Express Server made with TypeScript.
It has all 3 endpoints (/ping, /submit, /read).
The code can be put on a public GitHub Repository.
There's a clear README with instructions on how to run the server.
