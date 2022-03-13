# conf-dot-d-helper
Bash functions to assist with including supplemental config files

# Implement
To implement do the following
- copy this file to `/usr/local/bin`
- ensure application conf.d directory exists
- add the following lines to main app environment file

```
source /usr/local/bin/conf_helpers
confadd <app-name>

```
