# awesome-cog

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Cloud Optimized Geotiff resources.

## Overview

From [cogeo.org](http://cogeo.org)

> A Cloud Optimized GeoTIFF (COG) is a regular GeoTIFF file, aimed at being hosted on a HTTP file server, with an internal organization that enables more efficient workflows on the cloud.

## Tools

### General

- [rio-tiler](https://github.com/cogeotiff/rio-tiler): Core module to read data from a COG
- [rio-cogeo](https://github.com/cogeotiff/rio-cogeo): CLI + python module to easily create COG
- [rio-tiler-mosaic](https://github.com/cogeotiff/rio-tiler-mosaic): rio-tiler plugin to handler multiple overlapping dataset (was made as a separate module to keep rio-tiler simple)
- [rio-tiler-mvt](https://github.com/cogeotiff/rio-tiler-mvt): rio-tiler plugin to create vector tiles from a numpy array
- [rio-tiler-crs](https://github.com/cogeotiff/rio-tiler-crs): rio-tiler plugin to create tile in other CRS
- [cogeo-mosaic](https://github.com/developmentseed/cogeo-mosaic) devseed CLI+python module to create MosaicJSON (not linked directly to rio-tiler nor rio-cogeo)
- [cogeo-mosaic-tiler](https://github.com/developmentseed/cogeo-mosaic-tiler) Serverless map tiles from mosaics
- [cogeo-tiler](https://github.com/developmentseed/cogeo-tiler) devseed AWS stack - Dynamic tiler for simple COG.
- [titiler](https://github.com/developmentseed/titiler) Next-generation dynamic tiling, optionally serverless
- [rio-viz](https://github.com/developmentseed/rio-viz) devseed visualize COG in browser
- [cogeo-watchbot](https://github.com/developmentseed/cogeo-watchbot) devseed AWS stack - Create COG + MosaicJSON at scale
- [cogeo-watchbot-light](https://github.com/developmentseed/cogeo-watchbot-light) devseed AWS stack - Create COG at scale
- [cogeo-watchbot-fargate](https://github.com/developmentseed/cogeo-watchbot-fargate) devseed AWS stack - Create COG at scale using ECS fargate

### Landsat

- `rio-tiler-pds`
- [`landsat-cogeo-mosaic`](https://github.com/kylebarron/landsat-cogeo-mosaic): Create optimized Landsat 8 mosaics
- [`landsat-mosaic-latest`](https://github.com/kylebarron/landsat-mosaic-latest): Auto-updating most recent Landsat mosaics from SNS notifications
- [`landsat-mosaic-tiler`](https://github.com/kylebarron/landsat-mosaic-tiler): Serverless Landsat 8 dynamic tiling (fork of `cogeo-mosaic-tiler`)

### CBERS

- `rio-tiler-pds`

### NAIP

- [`naip-cogeo-mosaic`](https://github.com/kylebarron/naip-cogeo-mosaic): Create optimized mosaics of NAIP imagery.

### Other

- [`usgs-topo-tiler`](https://github.com/kylebarron/usgs-topo-tiler): Serverless tiling of USGS historical maps

## Applications and Examples

- [High-resolution Aerial Imagery for the U.S. (NAIP)](https://kylebarron.dev/naip-cogeo-mosaic/)
- <https://landsatlive.live>: Landsat dynamic tiling example

## Blog Posts

- [Dynamic map tiling with Cloud-Optimized GeoTIFFs](https://kylebarron.dev/blog/cog-mosaic/overview)
- [Vincent Sarago's COG Talk Series](https://medium.com/devseed/cog-talk-part-1-whats-new-941facbcd3d1)
