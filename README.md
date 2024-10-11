# One Photos Project

Welcome to One Photos!

## Setup

```bash
yarn install
```

## Developing

You can now run your One app in development:

```bash
  yarn dev
```

## Production

To build your app for production:

### Web

```bash
yarn build:web
```

### iOS

First, you'll need to generate the native code for your app:

```bash
yarn prebuild:native
```

Afterward, follow the instructions printed in the terminal to build and upload
your iOS app for distribution.
