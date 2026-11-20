# Mambattu/homebrew-tap

```sh
brew tap mambattu/tap
brew trust mambattu/tap   # newer Homebrew refuses untrusted third-party taps
```

| Name | Install | What it is |
|---|---|---|
| [orca](https://github.com/Mambattu/orca) | `brew install --cask mambattu/tap/orca` | Signed build of [stablyai/orca](https://github.com/stablyai/orca) with Mambattu patches. Installs as `Orca.app`, replaces an upstream install, and updates itself from Mambattu/orca releases. |
| orca@rc | `brew install --cask mambattu/tap/orca@rc` | Release candidates of the above. |
| [buzz-backend-docker](https://github.com/abipalli/buzz-backend-docker) | `brew install mambattu/tap/buzz-backend-docker` | Run Buzz agents on your own server: remote-agent backend for any Docker host. |

Formulae and casks are published by each project's release workflow; don't edit them by hand.

Moved from `abipalli/tap`. The old name still resolves, but to switch cleanly:

```sh
brew untap abipalli/tap && brew tap mambattu/tap && brew trust mambattu/tap
```

## Problems

Open a GitHub issue on the project the formula or cask comes from:
[Mambattu/orca](https://github.com/Mambattu/orca/issues) for `orca` and `orca@rc`,
[abipalli/buzz-backend-docker](https://github.com/abipalli/buzz-backend-docker/issues) for `buzz-backend-docker`.
