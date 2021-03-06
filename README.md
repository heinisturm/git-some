# git-some

A little helper script to quickly generate git commits.

## Usage

`git some [number of commits]` will generate `number of commits` commits in the current directory. Each commit will have one file with a semi-random name, `git-some.XXXXXXXX`, where `XXXXXXXX` is a wildcard for random characters. If you omit `number of commits`, `git some` will default to generate one commit. `git some` will not overwrite exiting files, but rather try to generate files that do not exist yet.

## Installation

Somewhere on your machine (preferrably your home directory), execute the following commands:

```
$ git clone https://github.com/GROSSWEBER/git-some.git
$ git-some/install.sh
```

`install.sh` will set up the `git some` alias for you.
