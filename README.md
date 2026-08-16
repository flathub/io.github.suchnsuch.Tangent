# Tangent Flathub Manifest
This is the Flathub manifest for the [Tangent](https://github.com/suchnsuch/Tangent) project.

It prepares, builds, and packages an [Electron](https://www.electronjs.org/) distribution. The `generated-sources.json` file is derived the source repository. It should be updated whenever dependencies of the project change. This can be done by installing [`flatpak-node-generator`](https://github.com/flatpak/flatpak-builder-tools/tree/master/node) and running:

```bash
flatpak-node-generator npm package-lock.json # <- Tangent's root package-lock file
```
