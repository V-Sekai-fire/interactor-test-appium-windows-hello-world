# interactor-test-appium-windows-hello-world

A WebDriver script that clicks through a sum in the desktop calculator app and reads the result back from its accessibility tree.

## What it is for

It is the smallest end-to-end check that a UI-automation server with the desktop driver can find a native app's controls by name, click them, and read a result.

## Build and run

With an `appium` server and its desktop driver running locally:

```sh
npm install
node test.js
```

## Licence

MIT; see `LICENSE`.
