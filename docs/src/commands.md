# Commands

These commands can be invoked with `zellij [SUBCOMMAND]`.

## `attach [session-name]`

Zellij will attempt to attach to an already running session, with the name
`[session-name]`.

The attach subcommand also will accept the optional `options` subcommand.

## `list-sessions`
short: `ls`

Will list all the names of currently running sessions.

## `kill-sessions [target-session]`
short: `k`

Will kill the session with the name of `[target-session]`, if it is currently
running.


## `options`

Can be used to change the behaviour of zellij on startup.
Will supercede options defined in the config file.
To see a list of options look [here](./options.md).

## `setup`

Functionality to help with the setup of zellij.

| Flag                                |  Description|
|:------------------------------------|------------------|
| --check                             |  Checks the configuration |
| --clean                             |  Start with default configuration|
| --dump-config                       |  Dump the default configuration file to stdout|
| --dump-layout [LAYOUT]      |  Dump a specified default layout file to stdout |
| --generate-completions [SHELL]      |  Generate completions for the specified shell|

# Flags
These flags can be invoked with `zellij --flag`.

| Flag                                |  Description|
|:------------------------------------|------------------|
| --help                             |   Display the help prompt |
| --debug                             |  Gather additional debug information |
| --version                       |  Print version information |
