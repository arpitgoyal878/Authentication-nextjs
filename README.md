# Next.js Authentication App

Explore a Next.js application designed to seamlessly integrate user authentication, providing a secure and intuitive user experience. This repository contains a fully functional Next.js project featuring a robust authentication system, complete with login, logout, and signup functionalities. Utilizing modern technologies such as Axios for API requests and react-hot-toast for elegant notifications, this app showcases best practices in handling user sessions and protecting routes.

## Key Features

- **Secure Authentication Flow**: Implementing a streamlined login and signup process, ensuring user credentials are handled securely. Passwords are encrypted using `bcryptjs` before storing in the database.
- **Email Confirmation**: Utilizing `Nodemailer` and `Mailtrap` to send email confirmations during the signup process, enhancing security and user verification.
- **Session Management**: Efficiently managing user sessions, with seamless integration of logout functionality to ensure user data protection.
- **Interactive UI**: Leveraging Tailwind CSS for a beautifully designed, responsive user interface that enhances usability and user engagement.
- **Client-Side Navigation**: Utilizing Next.js's built-in routing capabilities to provide a smooth, SPA-like experience across the authentication pages.
- **Toast Notifications**: Integrating `react-hot-toast` to display informative success and error messages, improving the overall user interaction.
- **Profile Management**: A dedicated profile page that allows users to view their details, reinforcing the app's authentication capabilities.
- **Data Storage**: Using MongoDB Atlas as the database solution for storing user details securely and efficiently.

Whether you're looking to implement authentication in your Next.js project or seeking inspiration for creating engaging user interfaces with Tailwind CSS, this repository offers valuable insights and practical code examples. Dive into the code to discover how to build secure, scalable, and user-friendly web applications with Next.js.


## Getting Started

To get a local copy up and running follow these simple steps.
1. Clone the repo
```bash
git clone https://github.com/arpitgoyal878/Authentication-nextjs.git
```

2. Go to the project folder
```bash
cd NextJS-Authentication
```

3. Install NPM packages
```bash
npm install
```
or
```bash
yarn install
```

4. Create `.env` file and enter valid data. (Refer to `.env.sample` file)

5. Run the development server
```bash
npm run dev
```
or
```bash
yarn dev
```

## Useful links
- NextJS - https://nextjs.org/docs/getting-started/installation
- Mailtrap - https://mailtrap.io/signin
- Nodemailer - https://www.nodemailer.com/
- MongoDb Atlas - https://www.mongodb.com/cloud/atlas/register
