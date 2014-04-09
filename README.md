# ![](https://gravatar.com/avatar/11d3bc4c3163e3d238d558d5c9d98efe?s=64) aptible/nginx

[![Docker Repository on Quay.io](https://quay.io/repository/aptible/nginx/status)](https://quay.io/repository/aptible/nginx)

NGiNX HTTP server.

## Installation and Usage

    docker pull quay.io/aptible/nginx
    docker run -P quay.io/aptible/nginx

To run with your own NGiNX site configuration file:

    docker run -P -v <sites-enabled-dir>:/etc/nginx/sites-enabled quay.io/aptible/nginx

## Available Tags

* `latest`: Currently NGiNX 1.4.7

## Deployment

To push the Docker image to Quay, run the following command:

    make release

## Copyright and License

MIT License, see [LICENSE](LICENSE.md) for details.

Copyright (c) 2014 [Aptible](https://www.aptible.com), [Frank Macreery](https://github.com/fancyremarker), and contributors.
