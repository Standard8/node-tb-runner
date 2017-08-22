# Thunderbird Runner

[![Build Status](http://img.shields.io/travis/standard8/node-tb-runner.svg?style=flat-square)](https://travis-ci.org/standard8/node-tb-runner)
[![Build Status](http://img.shields.io/npm/v/tb-runner.svg?style=flat-square)](https://www.npmjs.org/package/tb-runner)

[![NPM](https://nodei.co/npm/tb-runner.png?stars&downloads)](https://nodei.co/npm/tb-runner/)
[![NPM](https://nodei.co/npm-dl/tb-runner.png)](https://nodei.co/npm/tb-runner)

## Based on

Thunderbird runner is a fork of [node-fx-runner](https://github.com/mozilla-jetpack/node-fx-runner/blob/master/package.json),
but for [Thunderbird](https://www.thunderbird.net/).

## API

```
Usage: tb-runner [options] [command]

Commands:

start Start Thunderbird

Options:

-h, --help               output usage information
-V, --version            output the version number
-b, --binary <path>      Path of Thunderbird binary to use.
--binary-args <CMDARGS>  Pass additional arguments into Thunderbird.
-p, --profile <path>     Path or name of Thunderbird profile to use.
-v, --verbose            More verbose logging to stdout.
--new-instance           Use a new instance
--no-remote              Do not allow remote calls
--foreground             Bring Thunderbird to the foreground
-l, --listen <port>      Start the debugger server on a specific port.
```
