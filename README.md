# OpenTTD-jgrpp flatpak build

Upstream: https://github.com/JGRennison/OpenTTD-patches/releases

## How to build

```
flatpak-builder build --force-clean org.openttd.OpenTTD.jgrpp.yaml
```

Push to local repo

```
flatpak-builder --repo=/var/www/html/repo --force-clean build org.openttd.OpenTTD.jgrpp.yaml
```
