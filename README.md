# win-nxproxy

This repository is for making nxproxy for Windows available. You should be able to find 'nxproxy.exe' as well as its required DLLs in the release packages. They were automatically compiled and prepared via Github Actions using [the original source tree maintained and developed by ArcticaProject](https://github.com/ArcticaProject/nx-libs).

nxproxy can be used for improving SSH X11 forwarding over slow network. SSH already has its own compression option, but it treats data streams as simple raw bytes; it does not specifically target rendering bitmap data with better compression methods such as JPEG. The following post explores using nxproxy in X11 forwarding over SSH in more detail:

- [Boost X11 forwarding over SSH with JPEG/PNG Compression  
https://x410.dev/cookbook/boost-x11-forwarding-over-ssh-with-jpeg-png-compression](https://x410.dev/cookbook/boost-x11-forwarding-over-ssh-with-jpeg-png-compression)

If you prefer a fully integrated GUI solution based on nxproxy, try [X2Go Project (https://x2go.org)](https://x2go.org).
