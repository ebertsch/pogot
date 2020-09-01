pogot
=====

Command line utlities for pokemon go data

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/pogot.svg)](https://npmjs.org/package/pogot)
[![Downloads/week](https://img.shields.io/npm/dw/pogot.svg)](https://npmjs.org/package/pogot)
[![License](https://img.shields.io/npm/l/pogot.svg)](https://github.com/ebertsch/pogot/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g pogot
$ pogot COMMAND
running command...
$ pogot (-v|--version|version)
pogot/0.0.0 darwin-x64 node-v12.14.1
$ pogot --help [COMMAND]
USAGE
  $ pogot COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`pogot hello [FILE]`](#pogot-hello-file)
* [`pogot help [COMMAND]`](#pogot-help-command)

## `pogot hello [FILE]`

describe the command here

```
USAGE
  $ pogot hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ pogot hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/ebertsch/pogot/blob/v0.0.0/src/commands/hello.ts)_

## `pogot help [COMMAND]`

display help for pogot

```
USAGE
  $ pogot help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
