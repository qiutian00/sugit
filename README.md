# Git User Switch

Switch git user, email and signingKey at ease.

<img src="https://thumbs.gfycat.com/OfficialLiveImago-size_restricted.gif">


### Install

```
npm i -g sugit
```

### Usage

```
Usage: git-user [options]

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
git-user -r
```
