# rstudio-geospatial
RStudio with geospatial dependencies, based on [Rocker RStudio Docker container](https://hub.docker.com/r/rocker/geospatial) for CyVerse VICE. VICE requires additional configuration files (e.g. `nginx`) to be compatible with our Condor and Kubernetes orchestration. 

[![CircleCI](https://circleci.com/gh/cyverse-vice/rstudio-geospatial.svg?style=svg)](https://circleci.com/gh/cyverse-vice/rstudio-geospatial) [![license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://opensource.org/licenses/GPL-3.0) [![Project Supported by CyVerse](https://img.shields.io/badge/Supported%20by-CyVerse-blue.svg)](https://www.cyverse.org) [![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3246938.svg)](https://doi.org/10.5281/zenodo.3246938)


DockerHub        | description                               | size   | metrics | build status 
---------------- | ----------------------------------------- | ------ | ------- | --------------
[![DockerHub](https://img.shields.io/badge/DockerHub-brightgreen.svg?style=popout&logo=Docker)](https://hub.docker.com/r/cyversevice/rstudio-geospatial) | RStudio w/ geospatial depends | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial) | [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)

VICE Tools/Apps  | tag version                               | size   | metrics | build status 
---------------- | ----------------------------------------- | ------ | ------- | --------------
<a href="https://de.cyverse.org/de/?type=quick-launch&quick-launch-id=12f25023-b6b1-4f23-bbcc-49f0295da8c4&app-id=07e2b2e6-becd-11e9-b524-008cfa5ae621" target="_blank"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a> | latest | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial) | [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)
<a href="https://de.cyverse.org/de/?type=quick-launch&quick-launch-id=0d864f71-4be4-4217-aded-38940d0cbbcb&app-id=57330f1c-bbc6-11e9-9b4a-008cfa5ae621" target="_blank"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a> | 3.4.2 | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial:3.4.2.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial:3.4.2 "Get your own image badge on microbadger.com") | [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)
[![VICE](https://de.cyverse.org/Powered-By-CyVerse-blue.svg)]()| v3.5.0 | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial:3.5.0.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial:3.5.0 "Get your own image badge on microbadger.com")| [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)
[![VICE](https://de.cyverse.org/Powered-By-CyVerse-blue.svg)]()| v3.5.1 | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial:3.5.1.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial:3.5.1 "Get your own image badge on microbadger.com") | [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)
[![VICE](https://de.cyverse.org/Powered-By-CyVerse-blue.svg)]()| v3.5.2 | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial:3.5.2.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial:3.5.2 "Get your own image badge on microbadger.com")| [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)
<a href="https://de.cyverse.org/de/?type=quick-launch&quick-launch-id=f52b3c13-c16c-4ace-b689-7c90d9ab417d&app-id=0395a4e8-5265-11e9-82ce-008cfa5ae621" target="_blank"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a> | v3.5.3 | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial:3.5.3.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial:3.5.3 "Get your own image badge on microbadger.com") | [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)
<a href="https://de.cyverse.org/de/?type=quick-launch&quick-launch-id=a7509bf3-a019-4814-b9fa-f1788d0f68a0&app-id=33939454-bbb3-11e9-9fb7-008cfa5ae621" target="_blank"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a>| v3.6.0 | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial:3.6.0.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial:3.6.0 "Get your own image badge on microbadger.com")| [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)

# Instructions

## Run this Docker locally or on a Virtual Machine

To run these containers, you must first pull them from DockerHub

```
docker pull cyversevice/rstudio-geospatial:latest
```

```
docker run -it --rm -v /$HOME:/app --workdir /app -p 8787:80 -e REDIRECT_URL=http://localhost:8787 cyversevice/rstudio-geospatial:latest
```

The default username is `rstudio` and password is `rstudio1`. To reset the password, add the flag `-e PASSWORD=<yourpassword>` in the `docker run` statement.

## Build your own Docker container and deploy on CyVerse VICE

This container is intended to run on the CyVerse data science workbench, called [VICE](https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/index.html). 

Unless you plan on making changes to this container, you should just use the existing launch button above. 

###### Developer notes

To build your own container with a Dockerfile and additional dependencies, pull the pre-built image from DockerHub:

```
FROM cyversevice/rstudio-geospatial:latest
```

Follow the instructions in the [VICE manual for integrating your own tools and apps](https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/developer_guide/building.html).
