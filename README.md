# Ember

> Comes from the verb "embed", or "the one who embeds, an embe(dde)r".

`ember example.sol.js.ember -o example.sol` would evaluate `example.sol.js.ember` file with a located `js.ember` executable (extracted from the input file name), and output written to `example.sol`.

An EmberVM (`js.ember` in this case) shall have its arguments passed via the CLI, one-way communication only, e.g. `js.ember example.sol.js.ember -o example.sol`.

`example.sol.js.emberrc` is a configuration file for the according `example.sol.js.ember` file, read automatically.
`.emberrc` file is for the project-wide configuration.
