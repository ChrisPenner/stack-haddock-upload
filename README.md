# stack-haddock-upload

Hackage often fails to build documentation; this script allows you to manually upload documentation for your package.

Usage:

```shell
# From project root
$ stack-haddock-upload
```

The script will build docs using `stack haddock`, then upload them for the current version of the package you're in,
asking you for your hackage username and password. 
