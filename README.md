
# Teamable - User Profile Management Website

## Project Overview

Teamable is a user profile management website built with Vue.js and Express. Users can save and update their personal information through a user-friendly interface. The application is designed for easy deployment and maintenance, utilizing modern web development practices.

## Project Objectives

- Create a user-friendly interface for managing user profiles.
- Enable users to save and update their personal information.
- Implement server-side validation for user input.

## Technical Requirements

- **Languages and Libraries**: HTML, CSS, JavaScript, Vue.js, Express, MongoDB
- **Tools**: Visual Studio Code, Node.js, npm
- **Dependencies**: Listed in `package.json`

## Installation and Usage

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/zchean1216/Basic-User-Profile.git
    cd Basic-User-Profile/basic
    ```

2. **Install Dependencies**:
    ```sh
    npm install
    ```

3. **Run the Project**:
    ```sh
    npm run serve
    ```

4. **Open the Application**:
    - After running the above command, copy the local server URL (should be `http://localhost:3000`) from the terminal output and paste it into your web browser.

## File Structure

- **basic/**:
  - **index.html**: The main HTML file.
  - **App.vue**: The main Vue component containing the user profile interface.
  - **main.js**: Initializes the Vue app.
  - **server.js**: Sets up the Express server and API endpoints.
  - **validator.js**: Contains server-side validation functions.
  - **package.json**: Project metadata and dependencies.
  - **app.css/js**: Compiled CSS and JavaScript files for the frontend.

## API Endpoints

- **GET /get-profile**: Fetches user profile data.
- **POST /update-profile**: Updates user profile information.

## Tests

- Tests are written using Jest and Supertest.
    ```sh
    npm test
    ```

## Contact

For questions or feedback, contact:
- **Name**: Jayden Chia
- **Email**: zhengchean@gmail.com
