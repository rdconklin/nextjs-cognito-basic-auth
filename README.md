
# nextjs-cognito-basic-auth
=======
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Dependancies
- Install Node 18.18 or later
- Install NPM at least 10.9.2 
- Typescript 4.5.2
- Amplify library with an adapter for nextjs
  
## ENV
NEXT_PUBLIC_USER_POOL_ID
NEXT_PUBLIC_CLIENT_ID

Thes both reference the AWS Cognito resource ids the can be found
AWS->Cognito->

## Application Description
This application was created as proof concept of a nextjs application using AWS Cognito for Authentication and Authorization using amplify-library

Amplify-library functions imported
-singUp
-confirmSignUp
-signIn
-signOut
-resendSignUpCode
-autoSignIn
-type updateUswerAttributueOutput
-confirmUserAttribute
-updatePassword
-resetPassword
-confirmResetPassword
-fetchAuthSession
-fetchUserAttributes
-getCurrentUser

## Prequistes
### AWS Cognito
This applicaiton at a minimum requires AWS Cognito User Pool and User Groups.
Specifically you need the UserPool ID and Client ID

## Getting Started

First, run the development server:

```bash
npm run dev

```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

NOTE: The Application originally did not play nice with Dark Mode system themes and would automatically change all the default fonts to lighter colors that would blend in with the backgroun so I modified the default text color in a number of places to be a darker grey to improve readablilty.




