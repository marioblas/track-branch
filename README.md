# Track branch

Simple script for track a git remote branch using [NotifyOSD](https://wiki.ubuntu.com/NotifyOSD).

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

# Or indicate another branch with:
track-branch <remote>/<branch-name>
```

## License

MIT © [marioblas](https://github.com/marioblas)
