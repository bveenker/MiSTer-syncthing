<p align="center">
  <img width="128" height="128" src="./.github/syncthing_logo.png">
</p>

# MiSTer-syncthing

A script for running [Syncthing](https://syncthing.net/) on your MiSTer.

Thanks davewongillies for the original! Since I have encountered issues running syncthing v2 on MiSTer, this fork keeps syncthing on v1

## Prerequisites

* An Internet connected MiSTer

## Setup

1. Add the following to `/media/fat/downloader.ini`.

```ini
[bveenker/syncthing]
db_url = https://raw.githubusercontent.com/bveenker/MiSTer-syncthing/db/db.json.zip
```

2. Run `update` or `update_all` from the Scripts menu.
3. From the Scripts menu run `syncthing`.
4. Open [http://mister.local:8384](http://mister.local:8384)
