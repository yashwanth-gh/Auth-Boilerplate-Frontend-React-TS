# Auth Boilerplate Frontend (React with TypeScript)

Welcome to the Auth Boilerplate Frontend repository! This project provides a frontend interface built using React with TypeScript. It interfaces with the Authentication and Authorization Server Boilerplate Code backend to enable secure authentication and authorization features.

## Technologies Used

- **React with TypeScript**: A powerful combination for building robust and type-safe web applications.
- **Redux**: State management library for managing application state.
- **React Query**: Library for fetching, caching, synchronizing, and updating server state in React applications.
- **Tailwind CSS**: A utility-first CSS framework for quickly building custom designs.

## Configuration

Before running the project, ensure you have set up the following configurations:

- **Google OAuth**: Obtain your client ID from the Google Developer Console and set it in the environment variable `VITE_GOOGLE_CLIENT_ID`. Also, configure the redirect URI (`VITE_OAUTH_REDIRECT_URI`) to match your setup and the Google OAuth URI (`VITE_GOOGLE_OAUTH_URI`).
- **Server Endpoint**: Set the server endpoint (`VITE_SERVER_ENDPOINT`) to the URL where your Authentication and Authorization Server backend is hosted.

## Getting Started

To get started with using this frontend boilerplate code, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `npm install` or `yarn install`.
3. Set up your environment variables as described in the Configuration section.
4. Run the development server using `npm run dev` or `yarn dev`.
5. Access the frontend interface in your browser and start building your authentication and authorization features.

## Usage
The frontend interface provides a user-friendly interface for interacting with the Authentication and Authorization Server backend. It includes components for:

Signing up and signing in as both regular users and administrators.
Managing user accounts, including changing passwords, deleting accounts, and updating user information.
Administrative tasks such as viewing pending admin requests, approving pending requests, and managing user accounts.
## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.   
Happy coding! 🚀
