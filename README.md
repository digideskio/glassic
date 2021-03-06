glassic
==============

[![Build Status](https://travis-ci.org/mess110/glassic.svg?branch=master)](https://travis-ci.org/mess110/glassic)

[![glassic](wiki/snapshot.png)](https://mess110.github.com/glassic/)


Simple webview application generator for:

* android
* ios
* linux via nw.js
* mac via nw.js
* windows via nw.js

## Requirements

Developed with:

    $ node --version
    v0.12.7

## Installation

### Easy way

Use [glassic wizzard](https://github.com/mess110/glassic) to generate your application
and run *start.sh* from the generated archive.

### Extra easy way

Use [glassic wizzard](https://github.com/mess110/glassic) to generate your application
and use the build servers. *TODO*

### Hard way:

    git clone https://github.com/mess110/glassic.git
    cd glassic/
    vim config.json
    npm run glassic

This will install dependencies, compile according to [config.json](config.json)
and run the help command.

## Getting started

[![asciicast](https://asciinema.org/a/1r8ci9q4zupt8w0w0a0tils96.png)](https://asciinema.org/a/1r8ci9q4zupt8w0w0a0tils96)

Assuming you went through the installation steps, you now the git repositories
for your applications. They can be found in the [templates](templates/) folder.

Lets run the desktop app:

    npm run demo:linux

or build the android apk:

    npm run demo:android

[Documentation and more info can be found here](wiki/Home.md).

To view the list of commands:

    npm run help

## License

Please see [LICENSE](https://github.com/mess110/glassic/blob/master/LICENSE) for licensing details.

## Author

Cristian Mircea Messel, [@mess110](https://twitter.com/mess110)
