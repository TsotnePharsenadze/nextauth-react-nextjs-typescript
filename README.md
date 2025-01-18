<div align="center">
  <br/>
            <h1 style="font-size: 70px;">🔐 NextAuth</h1>
  <br/>
<table>
  <tr>
    <td><img width="400" alt="2FA Code Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/2faCodePage.PNG"></td>
    <td><img width="400" alt="Admin Actions Permissions Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/adminActionsPermissionsPage.PNG"></td>
    <td><img width="400" alt="Client Side Actions Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/clientSideActionsPage.PNG"></td>
  </tr>
</table>
  <p>
    <a href="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/TsotnePharsenadze/nextauth-react-nextjs-typescript" alt="contributors" />
    </a>
    <a href="">
      <img src="https://img.shields.io/github/last-commit/TsotnePharsenadze/nextauth-react-nextjs-typescript" alt="last update" />
    </a>
    <a href="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/network/members">
      <img src="https://img.shields.io/github/forks/TsotnePharsenadze/nextauth-react-nextjs-typescript" alt="forks" />
    </a>
    <a href="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/stargazers">
      <img src="https://img.shields.io/github/stars/TsotnePharsenadze/nextauth-react-nextjs-typescript" alt="stars" />
    </a>
    <a href="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/issues/">
      <img src="https://img.shields.io/github/issues/TsotnePharsenadze/nextauth-react-nextjs-typescript" alt="open issues" />
    </a>
  </p>
   
  <h4>
    <a href="#">Not avaliable because of unverified domain for RESEND</a>
    <span> · </span>
    <a href="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/readme.md">Documentation</a>
    <span> · </span>
    <a href="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/issues/">Report Bug</a>
    <span> · </span>
    <a href="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/issues/">Request Feature</a>
  </h4>
</div>

<br/>

## Features

1. **Credential Authentication/Authorization:**
   - Classical Email/Password Authentication;
3. **Protected/Public Routes:**
   - Controlled routes based on the current state of auth;
4. **Email Verification:**
   - Ensures email confirmation while registering new account;
5. **Github/Google Provider authentication:**
   - Implemented Github/Google authentication providers;
6. **Password recovery:**
   - Impemented an ability to recover password;
8. **Server/Client side actions:**
   - Settings route (after successfull authentication) displays "Client" and "Server" side fetching of data;
9. **Two Factor Authentication System:**
   - Once used is authenticated (with Classical Credential provider), he/she can enable 2FA;
10. **Update Settings once authorized:**
   - Settings route gives users an abiliy to manipulate their data, to change: Password, Email, Name, Role and givs users an ability to enable 2FA.


<br/>

## Installation

- Clone the repository:

  ```bash
  git clone https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript
  ```

- Navigate to the project directory:

  ```bash
  cd auth-savvy
  ```

- Install the dependencies:

  ```bash
  npm install
  ```

- Create .env file and setup all the neccessary env variables (given project uses Neon.tech as a rdms provider)

```

DATABASE_URL=""

AUTH_SECRET=""

GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""

GOOGLE_CLIENT_ID=""
GOOGLE_CLIENT_SECRET=""

RESEND_API_KEY=""

NEXT_PUBLIC_APP_URL=""
```

- Set up Neon.tech and generate/push Prisma models:

  1. Open new terminal and exec `npx prisma generate`
  2. then `npx prisma db push`
  
<br/>

## Usage

- Start the development server:

  ```bash
  npm run dev
  ```

- Open your browser and visit `http://localhost:3000` to access the application.

<br/>

## :camera: Screenshots

<table>
  <tr>
    <td><img width="400" alt="2FA Code Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/2faCodePage.PNG"></td>
    <td><img width="400" alt="Admin Actions Permissions Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/adminActionsPermissionsPage.PNG"></td>
  </tr>
  <tr>
    <td><img width="400" alt="Client Side Actions Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/clientSideActionsPage.PNG"></td>
    <td><img width="400" alt="Edit Settings Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/editSettingsPage.PNG"></td>
  </tr>
  <tr>
    <td><img width="400" alt="Login Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/loginPage.PNG"></td>
    <td><img width="400" alt="Password Recovery Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/passwordRecoveryPage.PNG"></td>
  </tr>
  <tr>
    <td><img width="400" alt="Registration Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/registrationPage.PNG"></td>
    <td><img width="400" alt="Server Side Actions Page" src="https://github.com/TsotnePharsenadze/nextauth-react-nextjs-typescript/blob/main/public/serverSideActionsPage.png"></td>
  </tr>
</table>


<br/>

## Contributing

Contributions are welcome! If you want to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes to the new branch.
- Open a pull request back to the main repository, including a description of your changes.
