My playground.

For the time being, I will make incompatible changes.

## Dependencies

- Python 3 (Probably works with Python 3.8 or later)
- [PyTorch](https://pytorch.org/get-started/locally/)
- See requirements.txt

We usually support the latest version. If there are bugs or compatibility issues, we will specify the version.

- [INSTALL-ubuntu](INSTALL-ubuntu.md)
- [INSTALL-windows](INSTALL-windows.md)

## waifu2x

The repository contains waifu2x pytorch implementation and pretrained models.
Command Line Interface and Web Application is supported. Training is currently not implemented.

See [waifu2x/README.md](waifu2x/README.md)

## Migration

If you have the old repository, remove the lfs hook with the following command.
(Currently this repository does not use lfs).

```
git lfs uninstall
git lfs prune
```

`git lfs uninstall` seems to affect globally, but I don't know how to disable `lfs` properly.
It may be better to clone it again.
