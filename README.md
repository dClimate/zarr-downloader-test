# Zarr Downloader Benchmark

This project compares the performance and functionality of Zarr v2 and Zarr v3 formats for accessing large-scale datasets stored on IPFS. The project includes two Jupyter Notebooks:

- `v2/compare_zarr_v2.ipynb`: Demonstrates the usage of Zarr v2.
- `v3/compare_zarr_v3.ipynb`: Demonstrates the usage of Zarr v3.

## Prerequisites

- Python 3.12 or higher
- [PDM](https://pdm.fming.dev/) for dependency management
- Jupyter Notebook or Jupyter Lab

## Setup Instructions

For v2:
```
cd v2
pdm install
pdm run python -m ipykernel install --user --name v2-env --display-name "Python (v2-env)"
```

For v2:
```
cd v3
pdm install
pdm run python -m ipykernel install --user --name v3-env --display-name "Python (v3-env)"
```

Open the respective notebook in Jupyter and set the kernel to the appropriate environment (v2-env or v3-env).

## License
This project is licensed under the MIT License.

Made with 🩵 by dClimate
