![MetaMask logo](logo.png?raw=true)
# MetaMask
MetaMask is a mobile web browser that provides easy access to websites that use the [Ethereum](https://ethereum.org/) blockchain.

For up to the minute news, follow our [Twitter](https://twitter.com/metamask_io) or [Medium](https://medium.com/metamask) pages.

To learn how to develop MetaMask-compatible applications, visit our [Developer Docs](https://metamask.github.io/metamask-docs/).

## MetaMask Mobile

### Building locally
The code is built using React-Native and running code locally requires a Mac or Linux OS.

- Install [Node.js](https://nodejs.org) **version 10 (latest stable) and yarn@1 (latest)**
    - If you are using [nvm](https://github.com/creationix/nvm#installation) (recommended) running `nvm use` will automatically choose the right node version for you.

- Install `xcode-select`
```
xcode-select --install
```

- Install `watchman`
```
brew install watchman
```

- Before starting, you need to install React Native dependencies:
    - [MacOs](https://facebook.github.io/react-native/docs/getting-started.html#installing-dependencies-1)
    - [Linux](https://facebook.github.io/react-native/docs/getting-started.html#installing-dependencies-2)
 -  Now clone this repo and then install all our dependencies

```bash
cd metamask-mobile
yarn install
```

- Running the app on Android:

```bash
yarn start:android
```

- Running the app on iOS.:
> This needs to be done at-least once before you can start building using xcode.
```bash
yarn start:ios:device
```

### Running tests:
 - Unit test:
```
yarn test:unit
```
 - E2E Tests (iOS)
```
yarn test:e2e:ios
```
 - E2E Tests (Android)
```
yarn test:e2e:android
```

### Troubleshooting

Visit [Troubleshooting for React Native](https://facebook.github.io/react-native/docs/troubleshooting#content)

## License

MetaMask Mobile is an exciting development for our team and our ecosystem. We've always been proud to offer the MetaMask browser extension under the MIT open source software license. We are still working through licensing considerations for the mobile application in light of a new delivery medium and our business goals. We are exploring many models, all with a significant open component, but we have not made any final decisions.

The source code for this beta is currently viewable under the below copyright. A license to use the mobile version will be distributed along with the mobile application. We believe it is important for our users to be able inspect and verify our code for trustworthiness, but we also wish to preserve our licensing options until we're certain what is best for MetaMask, our community, and our ecosystem. If you have any questions or comments, we would really appreciate hearing your feedback – you can reach us at mobile@metamask.io

© ConsenSys AG, 2016-2019

You are granted a limited non-exclusive license to inspect and study the code in this repository. There is no associated right to reproduction granted under this license except where reproduction is necessary for inspection and study of the code. You may not otherwise reproduce, distribute, modify or create derivative works of the code without our prior consent. All other rights are expressly reserved.
