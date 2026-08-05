# Asphyxia CORE Community Plugins

This repository is a community-plugin fork for
[Asphyxia CORE](https://asphyxia-core.github.io/). It currently adds
`popn@asphyxia` compatibility for pop'n music High Cheers while retaining the
other upstream community plugins.

## Installation

1. Install Asphyxia CORE. High Cheers support is tested with **CORE v1.60b**.
2. Download the latest package from this repository's
   [Releases page](https://github.com/haka5e/asphyxia-plugins/releases).
3. Copy the plugin directory you need into Asphyxia CORE's `plugins` directory.
   For pop'n music, copy the complete `popn@asphyxia` directory.
4. Restart CORE and confirm that the plugin appears in the WebUI.

Do not copy `savedata`, `config.ini`, databases, or machine-specific files into
a release. They may contain player data or local configuration and are not
required by the plugin.

## pop'n music compatibility

See [`popn@asphyxia/README.md`](popn@asphyxia/README.md) for supported game
versions, requirements, changes, and known limitations.

## Development checks

Install the development dependencies in an Asphyxia CORE plugin workspace and
run:

```shell
npm run typecheck
```

Launch CORE with `--dev` to enable plugin type checking and diagnostic output.

## Upstream

The original community plugin collection is maintained at
[asphyxia-core/plugins](https://github.com/asphyxia-core/plugins). Please keep
upstream attribution when redistributing derived plugins.
