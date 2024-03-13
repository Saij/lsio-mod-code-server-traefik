# Traefik - Docker mod for code-server/openvscode-server

This mod starts a Traefik container inside code-server/openvscode-server at container start if Docker-in-Docker is installed as mod.

In code-server/openvscode-server docker arguments, set an environment variable `DOCKER_MODS=saij/lsio-mods:code-server-traefik`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=saij/lsio-mods:code-server-traefik|linuxserver/mods:code-server-mod2`