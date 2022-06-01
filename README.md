# cypress-test-tiny

Take a look at `cypress/plugins/index.js`, there is a `console.log` in the
`file:preprocessor` event handler.

Run with `npm run cypress:run-ct`, if you look at the console the message "file:preprocess called!"
is not printed. If you run `npm run cypress:run`, the message is printed to the console (and
a few errors are thrown, but that doesn't really matter).