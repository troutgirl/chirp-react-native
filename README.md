# Chirp React Native Starter Project

This starter project isn't completely off the shelf, you will need to sign up to the [Chirp Developer Hub](https://developers.chirp.io/sign-up),
and copy your Chirp app key and secret into `App.js`.

## Setup

1. Clone the project

    `git clone https://github.com/chirp/chirp-connect-react-native-starter`

2. Install node_modules

    `cd chirp-connect-react-native-starter`

    `yarn install`

3. [iOS only] install dependencies

    `cd ios`

    `pod install`

4. Enter your application key and secret into `App.js`.

    `const key = 'YOUR_CHIRP_APPLICATION_KEY';`

    `const secret = 'YOUR_CHIRP_APPLICATION_SECRET';`

5. Run the demo.

    `react-native run-ios`

    `react-native run-android`
