# MapTool-flatpak

You can download the release to directly install the flatpak package with ```flatpak install --user net.rptools.MapTool.flatpak```

Alternatively you can download the linux .zip file from the official maptool release, put it in the folder with other files, and build the flatpak yourself with ```flatpak-builder --user --install --force-clean build-dir net.rptools.MapTool.yaml```, running the file with ```flatpak run net.rptools.MapTool```
