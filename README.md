# sugit

Switch git user, email and signingKey at ease.

[![npm](https://img.shields.io/npm/v/sugit.svg)](https://npmjs.com/package/sugit) [![](https://img.shields.io/npm/dt/sugit?style=flat&label=downloads&color=3b9648&labelColor=484848&logo=npm)](https://www.npmjs.com/package/sugit)


### Install

```
npm i -g sugit
```

### Usage

```
Usage: sug [options]

Switch git users quickly. Switches locally by default

Options:
  -V, --version  output the version number
  -g, --global   Switch global git user
  -d, --delete   Delete a git user from the listing
  -r, --reset    Deletes all data and resets
  -h, --help     display help for command
```


### Troubleshoot

In case this messes up any of your git configs because of bad input.
Just edit:

*Global* : `~/.gitconfig`
*Local Project* : `project/.git/config`

```
[user]
	email = luisli@gmail.com
	name = Luis Li
```

You can additionally reset the cli data store by running:

```sh
sug -r
```
