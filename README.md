# Entrypoint examples

Just a bunch of docker entrypoint examples.

## Common tasks

- change permissions (if root and run as user)
- get non local ip
- replace lines in files
- set envars
- changes in block, loop
- exec "$@"
- umask 0002 by default (group writable dunno why)
- if run as root modify user (su or similar)
- manage input args as list
- load envars from file `VAR [DEFAULT]`
- keystore shits
- load certs
- user id at run time as builtin
- get envars from list and pass as --key=value builtin (filter from envars and map with --key=value lambda render)
- get envars and save to yaml configuration file
- read envars from file (docker secrets, passwords, etc)
- include other files dynamically
- assert that
- create directories or modify permissions recursively (lookup find)
- random value generator
- ensure user is present in database
- set_fact
- lookup from shell
- user module allows to change user to that user
- retry until
