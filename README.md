# git-hash

[![Greenkeeper badge](https://badges.greenkeeper.io/blakek/git-hash.svg)](https://greenkeeper.io/)

> Just show the hash of a branch, tag, etc.

If you need to know the hash of some git object, just run `git-hash`.
All this does is runs `git rev-parse`.  However, this makes more sense to me, and `hash` is easier to remember than `rev-parse`.

## Usage

Show the (short) hash of the current branch:

```shell
git hash
```

Show the long hash of the current branch:

```shell
git hash -l

# short for: git hash --long
```

Show the hash of a branch, tag, etc.:

```shell
# show the hash of master
git hash master

# show the hash of a tag
git hash v1.0.4

# show the entire hash of feature/fun-stuff
git hash -l feature/fun-stuff
```

## Install

1. Either [clone this repo](https://help.github.com/articles/cloning-a-repository/) or [download the zip file](https://github.com/blakek/git-hash/archive/master.zip)
2. Add `git-hash` from this project to your $PATH

## License

MIT
