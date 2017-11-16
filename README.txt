Name: Kenneth High
Username: khigh

pmake is a perl script which parses and executes shell scripts. It is modeled after the make(1) program used with shell scripts in most *nix systems.

Note: the script is unable to execute Makefiles with a target 'dummy'. This was programmed in to prevent an uninitialized variable error which would crash the program on all Makefiles; acceptable losses and all that.
