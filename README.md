# Blog Website with Appwrite

This is a simple blog website built using Appwrite as a backend and hosted on Vercel.

## Features

- Create, read, update, and delete blog posts.
- User authentication and authorization.
- Simple and intuitive user interface.

## Technologies Used

- Frontend:
  - React.js
  - Appwrite JavaScript SDK
  - Material-UI for styling

- Backend:
  - Appwrite Backend as a Service (BaaS)

- Hosting:
  - Vercel

## Requirements

- Node.js
- Appwrite account
- Vercel account

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   https://github.com/SanjanaSingh1818/Appwrite_Blog.git


2. Install dependencies using npm:

   npm install

   
3. Create a `.env` file in the root directory of the project and add the following environment variables:

   REACT_APP_APPWRITE_ENDPOINT=https://your-appwrite-endpoint
   REACT_APP_APPWRITE_PROJECT_ID=your-appwrite-project-id
   REACT_APP_APPWRITE_API_KEY=your-appwrite-api-key

   ## Usage

To start the development server, run:

npm run dev


This will start the frontend server. Visit `http://localhost:3000` to view the app in your browser.

## Deployment

To deploy this app to Vercel, follow these steps:

1. Install the Vercel CLI globally:
   npm install -g vercel

2. Login to your Vercel account:
   vercel login

4. Deploy the project:
   vercel

   
Follow the prompts to deploy your app. Once deployed, you will receive a URL where your blog website is hosted.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


