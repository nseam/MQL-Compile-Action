# MQL Compile Action

<!-- [![Release][github-release-image]][github-release-link] -->
<!-- [![Docker image][docker-build-image]][docker-build-link] -->
[![Status][gha-image-action-master]][gha-link-action-master]
[![Status][gha-image-docker-master]][gha-link-docker-master]
[![Status][gha-image-lint-master]][gha-link-lint-master]
[![][tg-channel-image]][tg-channel-link]
[![][tg-chat-image]][tg-chat-link]
[![Edit][gitpod-image]][gitpod-link]

This GitHub Action compiles MQL programs.

## Inputs

### `Path`

Path to folder or file to compile.

Default: `.` (all files in the current folder are compiled).

### `MtVersion`

Platform version to use. Default: *5.0.0.2361*.

<!--
## Other Inputs

### `OptTrace`

Enables trace mode. It provides extensive debugging messages.

### `OptVerbose`

Enables verbose mode. It provides more detailed messages.
-->

<!--
## Outputs

### `foo`

Foo bar.
-->

## Example usage

```yaml
uses: fx31337/mql-compile-action@master
with:
  Path: '.'
```

### Support

- For bugs/features, raise a [new issue at GitHub](https://github.com/EA31337/MQL-Compile-Action/issues).
- Join our [Telegram group](https://t.me/EA31337) and [channel](https://t.me/EA31337_Announcements) for help.

<!-- Named links -->

[github-release-image]: https://img.shields.io/github/release/FX31337/MQL-Compile-Action.svg?logo=github
[github-release-link]: https://github.com/FX31337/MQL-Compile-Action/releases
[docker-build-image]: https://images.microbadger.com/badges/image/ea31337/mql-compile-action-action.svg
[docker-build-link]: https://microbadger.com/images/ea31337/mql-compile-action-action

[tg-channel-image]: https://img.shields.io/badge/Telegram-news-0088CC.svg?logo=telegram
[tg-channel-link]: https://t.me/EA31337_News
[tg-chat-image]: https://img.shields.io/badge/Telegram-chat-0088CC.svg?logo=telegram
[tg-chat-link]: https://t.me/EA31337

[gha-link-action-master]: https://github.com/FX31337/MQL-Compile-Action/actions?query=workflow%3AAction+branch%3Amaster
[gha-image-action-master]: https://github.com/FX31337/MQL-Compile-Action/workflows/Action/badge.svg
[gha-link-docker-master]: https://github.com/FX31337/MQL-Compile-Action/actions?query=workflow%3ADocker+branch%3Amaster
[gha-image-docker-master]: https://github.com/FX31337/MQL-Compile-Action/workflows/Docker/badge.svg
[gha-link-lint-master]: https://github.com/FX31337/MQL-Compile-Action/actions?query=workflow%3ALint+branch%3Amaster
[gha-image-lint-master]: https://github.com/FX31337/MQL-Compile-Action/workflows/Lint/badge.svg

[gitpod-image]: https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod
[gitpod-link]: https://gitpod.io/#https://github.com/FX31337/MQL-Compile-Action
