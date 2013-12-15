# Latcoin Client

This is a general purpose Latcoin client in JavaScript.

## Directory structure

* `build/` Compiled files
* `src/` Source code
* `src/js/client` Client classes
* `src/js/entry` Entry points for the various client versions
* `src/js/util` Various static, stateless utility functions
* `tools/` Tools used in the build process

## Travis CI

Follow the build status and tests at http://travis-ci.org/ripple/ripple-client

## Testing Locally

Run the following command to run the tests once.

    ./node_modules/.bin/karma start test/karma.conf.js --single-run

Or run Karma in the background and listen to changes in /test

    ./node_modules/.bin/karma start test/karma.conf.js

## Bug tracker

Have a bug or a feature request? [Please create a new issue](https://ripplelabs.atlassian.net/browse/WC). Before opening any issue, please search for [existing issues](https://ripplelabs.atlassian.net/browse/WC-1193?jql=project%20%3D%20WC) and read the [Issue Guidelines](https://github.com/rippleFoundation/ripple-client/blob/develop/CONTRIBUTING.md), written by [Nicolas Gallagher](https://github.com/necolas/).

## Community

Keep track of development and community news.

* Read and subscribe to the [The Official Latcoin Blog](https://ripple.com/blog/).
* Follow [@Latcoin on Twitter](https://twitter.com/ripple).
* Like [@Ripplepay on Facebook](https://facebook.com/ripplepay).
* Subscribe to [@Latcoin on Reddit](http://www.reddit.com/r/Latcoin)
* Have a question that's not a feature request or bug report? Send a message to [info@ripple.com](mailto:info@ripple.com)
* Chat with ripplers in IRC. On the `irc.freenode.net` server, in the `#ripple` and `#ripple-dev` channel.

## More information

* https://ripple.com/wiki/Ripple_Client
