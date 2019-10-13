# Ipfs version manger

simple.

## Commands

- `./bin/install [version]`: install specific version.
- `./bin/bin [version]`: return bin directory paths of specific version.
- `./bin/versions`: list versions that can be installed.
- `eval $(./bin/env [version])`: set up the environment of specific version.


## Requirements

- `curl`: required for `./bin/install` and  `./bin/versions`
- `tar`: required for `./bin/install`
- `xz`: required for `./bin/install`
- `git`: required for `./bin/versions`


```sh
apt-get update
apt-get install -y curl xz-utils git
```
