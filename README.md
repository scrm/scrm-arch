[![Project Status: Abandoned – Initial development has started, but there has not yet been a stable, usable release; the project has been abandoned and the author(s) do not intend on continuing development.](https://www.repostatus.org/badges/latest/abandoned.svg)](https://www.repostatus.org/#abandoned)

## Build Package
```bash
makepkg
```


## Check Package
```
namcap PKGBUILD
namcap <package file name>.pkg.tar.xz
```

## Perpare for upload
To create the tarball for uploading install `pkgbuild-introspection`
and execute:

```bash
mkaurball
```
