Docker Container for Jupyter
===

This Docker container is set up for Python3, HDF5, NetCDF, and Jupyter using an Alpine base image.

# Running
```
docker run -ti --name nb --rm -v $(pwd)/notebooks:/notebooks -p 8888:8888 quay.io/occ-data/docker-jupyter
```

