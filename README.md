# Track branch

Simple script for track a git remote branch using [NotifyOSD](https://wiki.ubuntu.com/NotifyOSD).

![](https://cloud.githubusercontent.com/assets/3719969/7668541/a9fe5616-fc35-11e4-9d8b-4ecd33618f2d.png)

## Install

```sh
sudo cp track-branch /usr/local/bin
mkdir $HOME/.track-branch && cp assets/git.png $_
```

## Usage

In your git project:

```sh
# Track the default branch (origin/master) with:
track-branch

# Or indicate another branch with: `track-branch <remote>/<branch-name>`, e.g.
track-branch origin/develop
```

## License

MIT © [marioblas](https://github.com/marioblas)
