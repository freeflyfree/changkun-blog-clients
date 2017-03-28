<img src="logo.png" alt="logo" height="120" align="right" />

# Changkun's Blog Clients

[*Changkun's Blog*](https://changkun.us/) *Desktop&Mobile Clients, powered by* [*Electron*](http://electron.atom.io) & [*React Native*](http://facebook.github.io/react-native/).

## Desktop Version

Desktop clients support `macOS/Windows/Linux(Ubuntu)` platform. If you would like to only build desktop version, the following instractions help you to build desktop clients.

To install dependencies:

```bash
npm install
# or
yarn install
```

To build all platform:

```bash
npm run build
# or
yarn run build
```

To build specific platform:

```bash
npm run build-mac       # for macOS x64
npm run build-win       # for windows x64
npm run build-linux     # for linux ubuntu x64
# or
yarn run build-mac
yarn run build-win
yarn run build-linux 
```

TO build release version to Github, you need provide your Github token, and change the provider and repository info in the `package.json`, then:

```bash
export GH_TOKEN="YOUR_TOKEN" npm run build-release
```

> Please note that 32-bit version is not recommended, I will never support that.

### Preview

<div style="display: flex; justify-content: center">
	<img src="assets/desktop.png" height=480>
</div>

## Mobile Version

Mobile Version is currently in development. You could check the [mobile](./mobile/Blog) folder for details.

Go to `./mobile/Blog`, then

To install dependencies:

```bash
npm install react-native-cli -g
npm install
# or
yarn install react-native-cli -g
yarn install
```

To run for iOS:

```bash
react-native run-ios
```

To run for Android:

```bash
react-native run-android
```

### Preview

<div style="display: flex; justify-content: center">
	<div style="border: solid; border-width: 1px;">
	<img src="assets/mobile1.png" height=480/>
	</div>
	<div style="border: solid; border-width: 1px;">
	<img src="assets/mobile2.png" height="480"/>
	</div>
</div>

## License

Copyright &copy; 2016 Changkun Ou. All rights reserved.

The code is distributed under the MIT license. See [LICENSE](./LICENSE) in this directory for more details.



