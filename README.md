# Boilerplate Code for Chrome Extension with TypeScript Support

This repository contains boilerplate code for creating a Chrome Extension with TypeScript support. TypeScript is a superset of JavaScript that provides static type checking and other advanced features to JavaScript developers. This boilerplate code is designed to help you get started quickly with developing Chrome extensions using TypeScript.

## Getting Started

To get started, you will need to clone this repository to your local machine. You can do this by running the following command in your terminal:

```bash
git clone https://github.com/egor-k/chrome-boilerplate.git
```

Once you have cloned the repository, you can install the dependencies by running the following command:

```bash
npm install
```

This will install all the required dependencies for the boilerplate code.


## Building the Extension

To build the extension, you can use the following command:

```bash
npm run build
```

This command will compile the TypeScript code into JavaScript and create a `dist` folder that contains the compiled code. 

You can then open the Chrome browser and navigate to `chrome://extensions/`. From there, you can enable developer mode and load the unpacked extension by selecting the `dist` folder in the cloned repository.

## Helpful links

- [Chrome Extension Developer Guide](https://developer.chrome.com/docs/extensions/mv3/)
- [Extensions Reloader](https://chrome.google.com/webstore/detail/extensions-reloader/fimgfedafeadlieiabdeeaodndnlbhid)