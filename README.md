# EmployWise Application Assingment

EmployWise is a React application that allows users to log in, view a list of users, edit user information, delete users, and search for users. The application handles token persistence and expiration, ensuring secure access to protected routes. It utilizes Reqres.in as a mock API for authentication and user data.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js (version 14 or higher)**: [Download Node.js](https://nodejs.org/)
- **npm**: Comes with Node.js

## Installation

Follow these steps to set up the project locally:

1. **Download the Zip File**: [Download Link](#)
2. **Extract the zip file** and open the folder in VSCode.
3. **Open the Terminal** in VSCode.
4. **Run the command** `npm install` to download the dependencies.
5. **Start the project locally**: Run the command `npm start`.

### To Clone the Repository

```bash
git clone https://github.com/kanchqn1322/employwise.git
```

Navigate to the project directory:

```bash
cd employwise
```

Install the dependencies:

```bash
npm install
```

This command installs all necessary packages listed in the `package.json` file.

## Running the Project

To start the application locally:

Start the development server:

```bash
npm start
```

This command runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Login Credentials

Use the following credentials to log in:

- **Email**: eve.holt@reqres.in
- **Password**: cityslicka

### Users List

After logging in, you'll see a list of users fetched from the API.

- Use the search bar to filter users by first or last name.
- Navigate through pages using the "Previous" and "Next" buttons.

### Edit User

- Click on the "Edit" button on a user's card to modify their details.
- Update the user's first name, last name, or email.
- Click "Update" to save changes.

### Delete User

- Click the "Delete" button on a user's card to remove them from the list.
- Confirm the deletion when prompted.

### Logout

- Click on the "Sign Out" button to log out.
- This will clear your token and redirect you to the login page.

## Assumptions and Considerations

### Mock API

The application uses Reqres.in as a mock API. Since it's a mock API, some functionalities like data persistence are simulated.

### Data Handling

- Editing or deleting a user updates the state locally.
- Changes are not persisted on the server due to API limitations.

### Error Handling

- The app includes basic error handling for network requests.
- Error messages are displayed to inform the user of any issues.

### UI/UX Design

- The UI is built using Material-UI (MUI).
- Efforts have been made to keep the UI consistent and user-friendly.

### Authentication

- Authentication is handled via a token received upon successful login.
- No actual user registration is implemented.

## Dependencies

The project relies on the following main dependencies:

- **React**: Library for building user interfaces.
- **React Router DOM**: For routing and navigation.
- **Axios**: For making HTTP requests to the API.
- **Material-UI (MUI)**: For UI components and styling.

## Project Structure

### Scripts

- **Start the development server**: `npm start`
- **Build the app for production**: `npm run build`
- **Run tests**: `npm test`

## Contact

For any queries, please contact:

- **Email**: tripathikan0713@gmail.com

Thank you for using EmployWise! We hope this application meets your needs.
