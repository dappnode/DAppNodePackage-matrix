# DAppnodePackage-matrix

[![DAppNodeStore Available](https://img.shields.io/badge/DAppNodeStore-Available-brightgreen.svg)](http://my.admin.dnp.dappnode.eth/#/installer/matrix.public.dappnode.eth)

This package runs a Matrix Synapse server.

## How to run this package

The `SYNAPSE_SERVER_NAME` environment variable is required. It is recommended to use your own DNS registered domain, so you can set SRV records and configure federation with other Matrix servers. 

Check [this link](https://github.com/matrix-org/synapse#id13) for more information on federation.

ACME support is enabled by default, so your certificates will be automatically created thanks to Let's Encrypt.

## Building

`docker-compose build`

### Start

`docker-compose up -d`

### View logs

`docker-compose logs -f`

### Stop

`docker-compose down`

### License

This package maintains the Apache License 2.0
