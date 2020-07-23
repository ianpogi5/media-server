# Home Media Server

Docker compose file I use in my RaspberryPi 4 home server

Softwares included:

- [transmission](https://docs.linuxserver.io/images/docker-transmission) - BitTorrent client
- [jackett](https://docs.linuxserver.io/images/docker-jackett) - Works as proxy server: it translates queries from apps into tracker-site-specific http queries, parses the html response, then sends results back to the requesting software.
- [radarr](https://docs.linuxserver.io/images/docker-radarr) - A fork of Sonarr to work with movies à la Couchpotato.
- [sonarr](https://docs.linuxserver.io/images/docker-sonarr) - It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. 
- [lidarr](https://docs.linuxserver.io/images/docker-lidarr) - Music collection manager for Usenet and BitTorrent users.
- [lazylibrarian](https://docs.linuxserver.io/images/docker-lazylibrarian) - Program to follow authors and grab metadata for all your digital reading needs.
- [plex](https://docs.linuxserver.io/images/docker-plex) - Organizes video, music and photos from personal media libraries and streams them to smart TVs, streaming boxes and mobile devices.
