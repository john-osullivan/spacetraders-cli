spice-traders-cli
=================

Command-Line Interface for SpiceTraders API

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/spice-traders-cli.svg)](https://npmjs.org/package/spice-traders-cli)
[![CircleCI](https://circleci.com/gh/https://github.com/john-osullivan/spacetraders-cli.git/tree/master.svg?style=shield)](https://circleci.com/gh/https://github.com/john-osullivan/spacetraders-cli.git/tree/master)
[![Downloads/week](https://img.shields.io/npm/dw/spice-traders-cli.svg)](https://npmjs.org/package/spice-traders-cli)
[![License](https://img.shields.io/npm/l/spice-traders-cli.svg)](https://github.com/https://github.com/john-osullivan/spacetraders-cli.git/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g spice-traders-cli
$ spacetraders COMMAND
running command...
$ spacetraders (-v|--version|version)
spice-traders-cli/0.5.4 linux-x64 node-v14.15.5
$ spacetraders --help [COMMAND]
USAGE
  $ spacetraders COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`spacetraders hello [FILE]`](#spacetraders-hello-file)
* [`spacetraders help [COMMAND]`](#spacetraders-help-command)

## `spacetraders hello [FILE]`

describe the command here

```
USAGE
  $ spacetraders hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ spacetraders hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/john-osullivan/spacetraders-cli/blob/v0.5.4/src/commands/hello.ts)_

## `spacetraders help [COMMAND]`

display help for spacetraders

```
USAGE
  $ spacetraders help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_
<!-- commandsstop -->
