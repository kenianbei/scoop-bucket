# scoop-bucket

[![Tests](https://github.com/kenianbei/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/kenianbei/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/kenianbei/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/kenianbei/scoop-bucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for [RetireTui](https://github.com/kenianbei/retiretui).

```pwsh
scoop bucket add kenianbei https://github.com/kenianbei/scoop-bucket
scoop install kenianbei/retiretui
```

This installs the `retiretui` command and the `retiretui-desktop` window, with a
Start Menu shortcut to the window. Excavator checks for a new release every four
hours and updates the manifest itself.
