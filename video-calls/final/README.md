# Dolby.io Communications Web SDK -- Getting Started with User Authentication using Auth0

This starter project demonstrates the mechanics of making a Voice and Video Call with Dolby.io and authenticate a user in your application using Auth0's Universal Login Page.

## Running the Sample Application

The sample can be run locally, by cloning the repository to your machine and then following the steps below.

### Specifying Auth0 Credentials

To specify the application client ID and domain, make a copy of `auth_config.json.example` and rename it to `auth_config.json`. Then open it in a text editor and supply the values for your application:

```json
{
  "domain": "{DOMAIN}",
  "clientId": "{CLIENT_ID}",
  "CONSUMER_KEY" : "{CONSUMER_KEY}",
  "CONSUMER_SECRET" : "{CONSUMER_SECRET}"
}
```

### Installation

After cloning the repository, run:

```bash
$ npm install
```

This will install all of the necessary packages in order for the sample to run.

### Running the Application

This version of the application uses an [Express](https://expressjs.com) server that can serve the site from a single page. To start the app from the terminal, run:

```bash
$ npm run dev
```

## What is Auth0?

Auth0 helps you to:

- Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, among others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
- Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
- Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
- Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
- Analytics of how, when and where users are logging in.
- Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free Auth0 account

1. Go to [Auth0](https://auth0.com/signup) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.

## Author

[Fatma Sena Ekiz](https://github.com/neptunel)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE.txt) file for more info.

## Learn More

For more information about Dolby.io Communications Web SDK, visit the [Dolby.io Communications Web SDK](https://docs.dolby.io/communications-apis/docs/js-overview) documentation.

For more information about Auth0 JavaScript SDK Quickstart, visit the [Vanilla JS Quickstart](https://auth0.com/docs/quickstart/spa/vanillajs/01-login) documentation. If you're having issues running the sample applications, [check the FAQ](https://github.com/auth0/auth0-spa-js/blob/master/FAQ.md)
