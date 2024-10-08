# Arr Stack  [![Lint and Test](https://github.com/bubylou/Arr-Stack/actions/workflows/test.yml/badge.svg)](https://github.com/bubylou/Arr-Stack/actions/workflows/test.yml) [![Release](https://github.com/bubylou/Arr-Stack/actions/workflows/release.yml/badge.svg)](https://github.com/bubylou/Arr-Stack/actions/workflows/release.yml) [![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/arr-stack)](https://artifacthub.io/packages/search?repo=arr-stack)

This repository contains several helm charts mostly aimed at deploying the various *arr apps such as sonarr, radarr, etc. to kubernetes. The goal for these charts is to provide a simple way to deploy the applications with good defaults, minimal code via common library chart, and big focus on added setup automation.

Further instructions for installing each chart are contained in the README inside the chart folder. To add this repository to helm run:

```bash
helm repo add arr-stack https://bubylou.github.io/Arr-Stack
helm repo update
```

You can then run `helm search repo arr-stack` to see the charts.

## Charts
| Name                                                                              | Description                |
| --------------------------------------------------------------------------------- | -------------------------- |
| [bazarr](https://github.com/bubylou/Arr-Stack/tree/main/charts/bazarr)            | Helm chart for bazarr      |
| [jellyfin](https://github.com/bubylou/Arr-Stack/tree/main/charts/jellyfin)        | Helm chart for jellyfin    |
| [jellyseerr](https://github.com/bubylou/Arr-Stack/tree/main/charts/jellyseerr)    | Helm chart for jellyseerr  |
| [lidarr](https://github.com/bubylou/Arr-Stack/tree/main/charts/lidarr)            | Helm chart for lidarr      |
| [lldap](https://github.com/bubylou/Arr-Stack/tree/main/charts/lldap)              | Helm chart for lldap       |
| [navidrome](https://github.com/bubylou/Arr-Stack/tree/main/charts/navidrome)      | Helm chart for navidrome   |
| [prowlarr](https://github.com/bubylou/Arr-Stack/tree/main/charts/prowlarr)        | Helm chart for prowlarr    |
| [qbittorrent](https://github.com/bubylou/Arr-Stack/tree/main/charts/qbittorrent)  | Helm chart for qbittorrent |
| [radarr](https://github.com/bubylou/Arr-Stack/tree/main/charts/radarr)            | Helm chart for radarr      |
| [readarr](https://github.com/bubylou/Arr-Stack/tree/main/charts/readarr)          | Helm chart for readarr     |
| [sonarr](https://github.com/bubylou/Arr-Stack/tree/main/charts/sonarr)            | Helm chart for sonarr      |
| [unpacker](https://github.com/bubylou/Arr-Stack/tree/main/charts/unpacker)        | Helm chart for unpacker    |
