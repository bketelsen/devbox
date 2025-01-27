---
title: Nim
---

Nim projects can be run in Devbox by adding Nim and Nimble to your project. For some platforms, Nimble may return an error if OpenSSL is not available, so we recommend including `openssl_1_1` in your packages as well

[**Example Repo**](https://github.com/jetpack-io/devbox/tree/main/examples/development/nim/spinnytest)

[![Open In Devbox.sh](https://jetpack.io/img/devbox/open-in-devbox.svg)](https://devbox.sh/github.com/jetpack-io/devbox?folder=examples/development/development/nim/spinnytest)

## Adding Nim to your Project

`devbox add nim nimble-unwrapped openssl_1_1`, or add the following to your `devbox.json`

```json
    "packages": [
        "nim",
        "nimble-unwrapped",
        "openssl_1_1"
    ]
```

This will install Nim 1.6.8. 
