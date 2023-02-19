# jwt-improve-security
Example how to imporve security for JSON Web Tokens

## Install
- Clone the rpository
- Run `yarn` in terminal
- Run `yarn start` in terminal

## How to use: first step
- Open `http://localhost:3010`
- Click on `Get token` button - this will gererate a JWT token
- Copy the token
- Paste the token to the textare and click on `Check token`
- Token must be shown

## How to use: second step
- Open the site from another brower or another IP address
- Use the previously generated token
- Paste the token to the textare and click on `Check token`
- Token will be invalid

## What happened
- We added an extra security layer to the JWT.
- We verify the visitor IP address and the User-Agent string
- If any of them change, the token is unusable.
