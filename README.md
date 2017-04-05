# Phoenix-Docker
## A Docker container for the Phoenix framework

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Docker Stars](https://img.shields.io/docker/stars/ilkerguller/phoenix.svg)](https://hub.docker.com/r/ilkerguller/phoenix/)
[![Docker Pulls](https://img.shields.io/docker/pulls/ilkerguller/phoenix.svg)](https://hub.docker.com/r/ilkerguller/phoenix/)

This image is based on the [official Elixir image](https://hub.docker.com/_/elixir/) and includes the features of that image.

### Image Contents (updated: 05/04/2017)

- Elixir 1.4.2
- Phoenix 1.2.3
- Node JS 7.x
- Yarn (NPM)

### Image Versions

The 'latest' tag on Docker Hub should always be reasonably in sync with the tip of 'master' within this repository via automated builds.

### How to use this image

```
docker run -it -v "$PWD":/app ilkerguller/phoenix
```

### Authors

* **Ilker Guller** - [website](http://ilkerguller.com) / [twitter](https://twitter.com/the_bluescreen)

See also the list of [contributors](https://github.com/Sly777/phoenix-docker/contributors) who participated in this project.

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
