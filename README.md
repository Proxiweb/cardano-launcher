# cardano-launcher Shelley

`cardano-launcher` is a Node.js module for starting
[cardano-wallet](https://github.com/input-output-hk/cardano-wallet)
and the Shelley
[cardano-node](https://github.com/input-output-hk/cardano-node).

Its primary user is
[Daedalus](https://github.com/input-output-hk/daedalus); however it
could be used by any Javascript application.


## Work In Progress

This is a draft of the API for [ADP-92](https://jira.iohk.io/browse/ADP-92).

See the generated docs at https://input-output-hk.github.io/cardano-launcher/modules/_index_.html.


## Block diagram

```
Daedalus
 |   |
 |   |
 |   |
 |  cardano-launcher
 |          |
 |   +------+---------------+
 |   |                     |
cardano-wallet -->  cardano-node
```


## Local Development

### `npm start`

Runs the project in development/watch mode.

### `npm run build`

Bundles the package to the `dist` folder.

### `npm test`

Runs the test watcher (Jest) in an interactive mode.
By default, runs tests related to files changed since the last commit.

### `npm run typedoc`

Generates API documentation to the `docs` folder.
