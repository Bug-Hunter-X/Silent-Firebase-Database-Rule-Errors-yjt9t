# Silent Firebase Database Rule Errors
This repository demonstrates a common but often overlooked issue in Firebase: errors caused by restrictive or incorrectly configured database rules.  The client-side code may appear correct, yet data operations fail due to server-side rule violations.  The example shows how silent failures can occur and how to improve error handling and debugging.

## Setup
1. Clone this repository.
2. Create a Firebase project.
3. Set up your Firebase project with the provided rules (`database.rules.json`)
4. Install the Firebase SDK: `npm install firebase`
5. Configure your Firebase credentials in `bug.js` and `bugSolution.js`.

## Running the Code
The provided javascript files showcase the problematic code, and the solution using proper error handling.