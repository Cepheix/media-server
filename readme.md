# General information

This project contains docker-compose file for running home media server.

# Components

Solution is composed of several components:

* radarr
* bazarr
* jackett
* qbittorrent

## Radarr

[Radarr](github.com/Radarr/Radarr) is the open source project for downloading and managing movies library. It is exposed on port: 7878

## Bazarr

[Bazarr](github.com/morpheus65535/bazarr) is the open source project for improving sonarr/radarr by adding subtitles download feature. It is exposed on port: 6767

## Jackett

[Jackett](github.com/Jackett/Jackett) is the open source project for generating rss feed links for tracket specific sites to be used by sonarr/radarr. It is exposed on port: 9117

## qBittorrent

[qBittorrent](github.com/qbittorrent/qBittorrent) is the open source project for downloading torrent files. It is exposed on port: 8080