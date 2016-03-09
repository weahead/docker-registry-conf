# We ahead's Docker Registry configuration

[![latest 1.0.0](https://img.shields.io/badge/latest-1.0.0-green.svg)](https://github.com/weahead/docker-registry-conf/releases/tag/v1.0.0)

Docker image that puts configuration for Docker Registry on a volume at `/usr/local/etc/registry` via [confd](https://github.com/kelseyhightower/confd).

For use with [Rancher](http://rancher.com/), because configuration files use Rancher's [metadata service](http://docs.rancher.com/rancher/rancher-services/metadata-service/).

Based on [`weahead/conf`](https://github.com/weahead/docker-conf).


## License

[X11](LICENSE)
