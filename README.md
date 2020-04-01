

1. Clone the repo
2. Change into the repo folder
3. Create a copy of the .env.tpl file named .env in the root dir
4. Add the following environment variables to the .env file

   - BOT_GITHUB: github account that will create the pull rquest
   - GITHUB_AUTH_TOKEN: auth token from the bot github account https://github.com/settings/tokens
   - RECAPTCHA: from google recaptcha site https://www.google.com/recaptcha (only needed for production)

   ```
   NODE_ENV=
   BOT_GITHUB_USER=
   GITHUB_AUTH_TOKEN=
   RECAPTCHA_KEY=
   RECAPTCHA_SECRET=
   ```

5. Run `npm install`
6. Run `nodemon` to start a local server
7. See the page at localhost:3000
