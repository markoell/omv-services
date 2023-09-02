# Docker Compose Files for Private Home Server

This repository contains a collection of Docker Compose files for running various services on a private home server that uses OpenMediaVault and Portainer.

## Prerequisites

Before using these Docker Compose files, you should have the following:

* An OpenMediaVault installation running on your home server
* Portainer installed and running on your home server

## Installation

To use these Docker Compose files, follow these steps:

1. Clone this repository to your home server using the following command:

```bash
git clone https://github.com/your_username/your_repo.git
```

2. Navigate to the directory containing the Docker Compose file for the service you want to install.

3. Edit the Docker Compose file to suit your needs. You may need to change environment variables, ports, volumes, and other settings to match your setup.

4. Run the following command to start the service:

```bash
    docker-compose up -d
```

## Available Services

This repository currently contains Docker Compose files for the following services:

* Resilio Sync
* Duplicati

These services might follow:

* [ ] Plex Media Server
* [ ] Transmission BitTorrent Client
* [ ] Sonarr
* [ ] Radarr
* [ ] Lidarr
* [ ] Jackett
* [ ] Tautulli


Each service has its own Docker Compose file, which can be found in the relevant directory.

## Contributing

If you would like to contribute to this repository, please feel free to submit a pull request. Contributions are always welcome!

## License

This repository is licensed under the MIT License. See the LICENSE file for details.
