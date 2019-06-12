# rstudio-geospatial
RStudio with geospatial dependencies, based on [Rocker RStudio Docker container](https://hub.docker.com/r/rocker/geospatial) for CyVerse VICE. VICE requires additional configuration files (e.g. `nginx`) to be compatible with our Condor and Kubernetes orchestration. 

[![Project Supported by CyVerse](https://img.shields.io/badge/Supported%20by-CyVerse-blue.svg)](https://www.cyverse.org) [![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

image            | description                               | size   | metrics | build status 
---------------- | ----------------------------------------- | ------ | ------- | --------------
[![DockerHub](https://img.shields.io/badge/DockerHub-brightgreen.svg?style=popout&logo=Docker)](https://hub.docker.com/r/cyversevice/rstudio-geospatial) | RStudio R v3.5.3 w/ geospatial depends | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial) | [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/tswetnam/emsi-rstudio)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)
[![VICE](https://img.shields.io/badge/CyVerse-VICE-blue.svg?style=popout&logo=Docker&color=#1488C6)]()| VICE RStudio R v3.5.3 w/ geospatial depends | [![](https://images.microbadger.com/badges/image/cyversevice/rstudio-geospatial.svg)](https://microbadger.com/images/cyversevice/rstudio-geospatial) | [![](https://img.shields.io/docker/pulls/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial)  |  [![](https://img.shields.io/docker/automated/cyversevice/rstudio-geospatial.svg)](https://hub.docker.com/r/cyversevice/rstudio-geospatial/builds)

# Instructions

## Run Docker locally or on a Virtual Machine

To run the RStudio container, you must first pull them from DockerHub, or activate a [CyVerse Account](https://user.cyverse.org/services/mine).

A Docker container for running RStudio is hosted on DockerHub.

```
docker pull cyversevice/rstudio-geospatial:3.5.3
```

```
docker run -it --rm -d -p 8787:8787 -e PASSWORD=rstudio1 cyversevice/rstudio-geospatial:3.5.3
```

The default username is `rstudio` and password is `rstudio1`

## Run Docker container in CyVerse VICE

This container is run on the CyVerse data science workbench, called [VICE](https://cyverse-visual-interactive-computing-environment.readthedocs-hosted.com/en/latest/index.html). 

Unless you plan on making changes to this container, you should just use the existing launch button above. 

###### Developer notes

To test the container locally:

```
docker run -it --rm -v /$HOME:/app --workdir /app -p 8787:80 -e REDIRECT_URL=http://localhost:8787 cyversevice/rstudio-geospatial:3.5.3
```

The default username is `rstudio` and the default password is `rstudio1`
