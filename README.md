# Tree files for Ultramarine and tauOS variants

[![Build and deploy OSTree image](https://github.com/Ultramarine-Linux/ostree-config/actions/workflows/ostree.yml/badge.svg)](https://github.com/Ultramarine-Linux/ostree-config/actions/workflows/ostree.yml)

# 🛠️ Dependencies

Please make sure you have these dependencies first before building.

```
rpm-ostree
melody
just
```

Please note that building ISOs also require the following dependencies.

```
lorax
```

# 🏗️ Building

Simply clone this repo, then:

```sh
just build-image <ultramarine|tau>/<variant>
```

ISOs can be built using:

```sh
just isos/build-<ultramarine|tau> <variant>
```
