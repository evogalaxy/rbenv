# munin

Installation of Rbenv, Ruby and some default gems.

## Tasks

Everything is in the `tasks/main.yml` file.

## Available variables

* `rbenv_version`: Rbenv version to install ;
* `rbenv_ruby_version`: Ruby version to install ;
* `rbenv_root`: install path for Rbenv ;
* `rbenv_repo`: repository location ;
* `rbenv_plugins`: list of Rbenv plugins to install.

The role must be specified with a `username` variable :

```
roles:
- { role: rbenv, username: 'johndoe' }
```
