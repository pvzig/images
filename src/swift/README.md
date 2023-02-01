# Swift

## Summary

Develop Swift applications.

| Metadata | Value |  
|----------|-------|
| *Categories* | Languages |
| *Image type* | Dockerfile |
| *Published image* | ghcr.io/pvzig/images/swift |
| *Available image variants* | 5.7-jammy, 5.7-focal, 5.7-bionic, 5.7-centos7, 5.7-amazonlinux2, 5.6-focal, 5.6-bionic, 5.6-centos7, 5.6-amazonlinux2 |
| *Supported architecture(s)* | x86-64, arm64/aarch64 for some distros |
| *Works in Codespaces* | Yes |
| *Container host OS support* | Linux, macOS, Windows |
| *Container OS* | Debian, centOS, Amazon Linux |
| *Languages, platforms* | Swift |
| *Contributors* | [0xTim](https://github.com/0xTim), [adam-fowler](https://github.com/adam-fowler), [cloudnull](https://github.com/cloudnull), [pvzig](https://github.com/pvzig) |

## Using this image

You can directly reference pre-built versions of `Dockerfile` by using the `image` property in `.devcontainer/devcontainer.json` or updating the `FROM` statement in your own  `Dockerfile` to one of the following. An example `Dockerfile` is included in this repository.

- `ghcr.io/pvzig/images/swift` (latest)
- `ghcr.io/pvzig/images/swift:5.7` (or `5.7-jammy`, `5.7-amazonlinux2` to pin to an OS version)
- `ghcr.io/pvzig/images/swift:5.6` (or `5.6-focal`, `5.6-centos7` to pin to an OS version)

Refer to [this guide](https://containers.dev/guide/dockerfile) for more details.

#### Installing Node.js

Given JavaScript front-end web client code written for use in conjunction with a Go back-end often requires the use of Node.js-based utilities to build, you can use a [Node feature](https://github.com/devcontainers/features/tree/main/src/node) to install any version of Node by adding the following to `devcontainer.json`:

```json
{
  "features": {
    "ghcr.io/devcontainers/features/node:1": {
      "version": "latest"
    }
  }
}
```


## License

Copyright (c) Visual Studio Code Swift extension project. All rights reserved.

Licensed under the MIT License. See [LICENSE](https://github.com/swift-server/swift-dev-container/blob/main/LICENSE).
