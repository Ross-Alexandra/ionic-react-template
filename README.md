# Ionic React Template
A GH template for my Ionic/React front ends. Automatically packages:

    @ross-alexandra/react-utilities
    lodash
    @emotion/styled

This react template uses Typescript, ESlint, & Jest.

## Development
### Android API version
For unknown reasons, using `ionic` with `capacitor` may not work with
live reload on any Android API < 29. Please ensure you're using API_29 or greater
to ensure that you will be able to develop with live reload (using `npm run start:android`).

### VPNs
Note, if you're trying to develop on a read device, running a VPN will cause the
app to render as a white screen.

## Using Cordova Plugins
https://capacitorjs.com/docs/v2/cordova/using-cordova-plugins
```
    npm install @ionic-native/{name}

    // -- or --

    npm install @awesome-cordova-plugins/{name}
    npm install cordova-plugin-{name}
        
    // -- then --

    npx cap sync
```
