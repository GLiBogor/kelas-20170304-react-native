# Kelas React Native

This repository contains React Native example app from Kelas GLiB that held at [Rumah Btech](https://www.google.com/maps/uv?hl=en&pb=!1s0x2e69c45d60231907%3A0x95b9c9ebfa9b4767!2m19!2m2!1i80!2i80!3m1!2i20!16m13!1b1!2m2!1m1!1e1!2m2!1m1!1e3!2m2!1m1!1e5!2m2!1m1!1e4!3m1!7e115!4s%2Fmaps%2Fplace%2Frumah%2Bbtech%2F%40-6.5672637%2C106.7808132%2C3a%2C75y%2C14.79h%2C90t%2Fdata%3D*213m4*211e1*213m2*211sRFdklRIdUAGqKiNGWhyz-g*212e0*214m2*213m1*211s0x0%3A0x95b9c9ebfa9b4767!5srumah%20btech%20-%20Google%20Search&imagekey=!1e2!2sRFdklRIdUAGqKiNGWhyz-g&sa=X&ved=0ahUKEwjvhrX_zuTSAhWIRI8KHar8C1sQpx8IhQEwDA) (previously with Abraincode at [Keboencoding](https://www.google.co.id/maps/place/Keboen+Coding+-+IT+Community/@-6.3621547,106.8384558,15z/data=!4m2!3m1!1s0x0:0x813f0df3a09fcde5?sa=X&ved=0ahUKEwi9rsrT_rzSAhUUTo8KHYB4CTcQ_BIIajAO)

### Presentation slide

Please [download here](https://github.com/herpiko/kelas-20170304-react-native/raw/master/assets/ReactNative.pdf).

Some lines of code also explained in comments.

### Requirements

- Nodejs 6.x
- Android SDK. When you deploying for the first time, you'll be asked to fill the requirements gap (Build-tools, Android Platform SDK, Android Support Repository, etc). Install them via Android SDK.
- The versions that used when this documentation written were : `react-native 0.42.0`, `react-native-cli 2.0.1`

#### Simple HTTP API Server

- The app depends on an API, see [https://github.com/herpiko/wikipedia-featured-simple-api-example](https://github.com/herpiko/wikipedia-featured-simple-api-example).


### Preparation
- Setup environment variable correctly for `JAVA_HOME` and `ANDROID_HOME`
- Install React Native CLI globally, `npm install -g react-native-cli`
- Enter the working dir then install the dependencies, `npm run install`
- Prepare the emulator or device
- Change the `HOST` address to your own deployed API server.

### Deploy

- In other terminal session, run `react-native start` to fire packager microservice (live on port 8081).
- For Android, `react-native run-android`
- For iOS, `react-native run-ios`
- There is Live Reload and Hot Reload feature. Setup the correct address (packager) on dev settings if you want to use them.

### Build an installable APK file

You need to sign the APK. Please consult the [official documentation](https://facebook.github.io/react-native/releases/0.42/docs/signed-apk-android.html).

### TODO

- Step by step tutorial

### Screenshot

![alt text](./assets/android.png)
![alt text](./assets/ios.png)

