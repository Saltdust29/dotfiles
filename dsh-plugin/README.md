# dsh-plugin

DSH (DeepSeek Harness) plugin sources, one subdirectory per plugin.

- Each plugin keeps its own `package.json`, build script and `README.md`.
- Which plugins are enabled lives in `~/.dsh/settings.yaml`, not here.
- A plugin that has its own repository can be linked in (submodule or symlink)
  instead of copied.
