<h1 align="center">
  <br>
  <kbd>
    <img src="https://image.prntscr.com/image/YrkdAm5xSxe0MmkqrvGeJA.png" alt="Animavita" height="525" width="725">
  </kbd>
  <br>
  <h1 align="center"><b> :panda_face: Food Delivery App</b> </h1>
  <br><br>
</h1>

<p align="center">A minimal, clean and beautiful mobile app to help people find the foods to delivery and change the world.</p>

<p align="center"><i>"How to save a life?" - The Food Delivery</i> </p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/progress-40%25-brightgreen.svg" alt="PRs Welcome">
  </a>
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/contribuition-welcome-brightgreen.svg" alt="PRs Welcome">
  </a>
  <a href="https://saythanks.io/to/wendelfreitas">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
<a href="https://www.repostatus.org/#wip"><img src="https://www.repostatus.org/badges/latest/wip.svg" alt="Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public." /></a>  
</p>

<p align="center">
  <a href="#blush-why">Overview</a> •
  <a href="#dizzy-roadmap">Roadmap</a> •
  <a href="#zap-tech-stack">Tech Stack</a> •
  <a href="#iphone-1">Test</a> •
  <a href="#eyes-1">Version</a> •

</p>

<p align="center">
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/1.PNG" alt="1">
  </kbd>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/2.PNG" alt="2">
  </kbd>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/3.PNG" alt="3">
  </kbd>
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/4.PNG" alt="4">
  </kbd>
    &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/5.PNG" alt="5">
  </kbd>
    &nbsp;&nbsp;&nbsp;&nbsp;
  <kbd>
    <img width="250" style="border-radius: 5px" height="450" src="screenshots/6.PNG" alt="6">
  </kbd>
</p>

## :blush: **Overview?**

Animavita is a combination of two Latin words, ‘Animal’ and ‘Vitae’, which means respectively ‘Animal’ and ‘Life’. This is an idea to create or animate something that was born a while ago, when I realized that facebook is used to publicize adoption and also ask for help for animals that lives on the streets.

Animavita's purpose is not to change how people use facebook to the activities described above, but to centralize the helpful information in a single application. Anyone can make an adoption request, but it doesn’t mean that the pet will be automatically adopted. It means that the person interested can talk to the person who registered the pet, allowing both sides to have a conversation, and the user to research and decide his favorite pet.

## :dizzy: **Roadmap**

Check the [Roadmap](/ROADMAP.md) to more details about itens below.

-   [ ] Rescue system (WIP)
-   [ ] Write CONTRIBUTING.md + Install instructions
-   [ ] Make it work on IOS
-   [ ] Write tests in backend
-   [ ] Write tests in frontend
-   [ ] Transform into responsive
-   [ ] Create Landing Page
-   [ ] i18n
-   [ ] Offline-first
-   [ ] Create/Apply Dataloaders
-   [ ] Update to latest React Native version

## **Install instructions**

### Getting Started

#### 1) Clone & Install Dependencies

- 1.1) `git clone https://github.com/funnyjerry/react-native-homeautomation-app.git`
- 1.2) `cd react-native-homeautomation-app` - cd into your newly created project directory.
- 1.3) Install NPM packages with `yarn install`
        **Note:** NPM has issues with React Native so `yarn` is recommended over `npm`.
- 1.4) **[iOS]** `cd ios` and run `pod install` - if you don't have CocoaPods you can follow [these instructions](https://guides.cocoapods.org/using/getting-started.html#getting-started) to install it.
- 1.5) **[Android]** If you haven't already generated a `debug.keystore` file you will need to complete this step from within the `/android/app` folder. Run `keytool -genkey -v -keystore debug.keystore -storepass android -alias androiddebugkey -keypass android -keyalg RSA -keysize 2048 -validity 10000`

#### 2) Start your app

- 2.1) **[iOS]** Build and run the iOS app, run `react-native run-ios` (to run on simulator) or `react-native run-ios --device` (to run on real device) from the root of your project. The first build will take some time.
- 2.2) **[Android]** If you haven't already got an android device attached/emulator running then you'll need to get one running (make sure the emulator is with Google Play / APIs). When ready run `react-native run-android` from the root of your project.

## :zap: **Tech Stack**

<h1 align="center">
  <img src="https://miro.medium.com/max/2600/1*pD7ShcZ7YHIMXe2mgiFzbg.png" alt="Stack" height="150" width="600">
  <br>
</h1>

-   [Facebook Login](https://github.com/facebook/react-native-fbsdk)
-   [React Native](https://github.com/facebook/react-native)
-   [Styled Components](https://www.styled-components.com/)
-   [Reactotron](https://infinite.red/reactotron)
-   [Eslint](https://eslint.org/)
-   [Redux](https://github.com/reduxjs/react-redux)
-   [MongoDB](https://www.mongodb.com/)
-   [Formik + Yup](https://jaredpalmer.com/formik/)
-   [Apollo](https://apollographql.com)
-   [GraphQL](https://github.com/facebook/graphql)
-   [Kraken](https://github.com/wendelfreitas/kraken)
-   [OneSignal](https://onesignal.com)
-   [AWS](https://aws.amazon.com/pt/)
-   [Redux-Persist](https://github.com/rt2zz/redux-persist)

## :iphone: **Test**

- [x] Test on Android
- [x] Test on iOS

## :eyes: **Version**
- [ ] React-Native 
- [x] Expo 35
