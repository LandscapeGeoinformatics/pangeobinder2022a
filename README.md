# conda environment.yml for binder

Python Pangeo-inspired notebooks for teaching and research in Geoinformatics and Earth Sciences/ML

[Landscape Geoinformatics](https://landscape-geoinformatics.ut.ee) - [Alex Kmoch](https://kodu.ut.ee/~kmoch/)


https://mybinder.org/v2/gh/LandscapeGeoinformatics/pangeobinder2022a/HEAD?labpath=index.ipynb

## Docker image local

https://hub.docker.com/r/allixender/pangeobinder2022a/tags

```
docker pull allixender/pangeobinder2022a:latest
```

## License and terms of usage

Adapted by Alexander Kmoch and Evelyn Uuemaa

We hope that the materials provided here would be helpful for others. Thus, we share all the lesson materials openly, and also our source codes and lesson materials are openly available.

**These materials and code snippets are licensed** with **Creative Commons Attribution 4.0 International licence** and **MIT license**.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" align="left" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

## Other packages for consideration

Compare with fixed package versions from Pangeo images, e.g. Dask, to avoid incompatibilities (like numpy<>datashader)

Currently no deep-learning is considered here, mostly base geospatial/gis

- odc-stac
- s2geometry (with swig python bindings)
- python-language-server
- jupyter-panel-proxy (not sure if needed)
- formatting and testing (black, pytest)
- pangeo-ml image (tbc), lightgbm
