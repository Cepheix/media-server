# General information

This project contains docker-compose file for running home media server.

# Configuration

All necessary variables are provided in example.env file. Set them as environment variables or create .env file and store them there.

# Components

Solution is composed of several components:

* radarr
* sonarr
* bazarr
* jackett
* qbittorrent

## Radarr

[Radarr](https://github.com/Radarr/Radarr) is the open source project for downloading and managing movies library. It is exposed on port: 7878

## Sonarr

[Sonarr](https://github.com/Sonarr/Sonarr) is the open source project for downloading and managing tv series library. It is exposed on port: 8989

## Bazarr

[Bazarr](https://github.com/morpheus65535/bazarr) is the open source project for improving sonarr/radarr by adding subtitles download feature. It is exposed on port: 6767

## Jackett

[Jackett](https://github.com/Jackett/Jackett) is the open source project for generating rss feed links for tracket specific sites to be used by sonarr/radarr. It is exposed on port: 9117

## qBittorrent

[qBittorrent](https://github.com/qbittorrent/qBittorrent) is the open source project for downloading torrent files. It is exposed on port: 8080