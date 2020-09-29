# OAuthAssignment

## Introduction
This is a small web application that is using OAuth2.0 standard-protocol to handle google single sign-on and display google account's protected resources such as  profile picture and the email.

## Installation
1. You will need latest Node.js installed on your server

2. Clone the repository

3. Install dependencies
```npm install```

4. Create a client ID and client secret using Google API Console.

5. Set below enviroment variables
```
GOOGLE_CLIENT_ID = <your google client id>
GOOGLE_CLIENT_SECRET = <your google client secret>
```

6. Run the server
```
node index.js 
```
