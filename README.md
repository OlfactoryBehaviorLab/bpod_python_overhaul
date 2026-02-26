# Development setup for the Bpod python overhaul

This _dummy_ python package serves to integrate `bpod-rig`, `bpod-gui`, and `bpod-core` into a singular uv workspace
for development purposes.

## Development Setup

We utilize astral's uv to manage virtual environments and dependencies.
Visit the uv documentation [here](https://docs.astral.sh/uv/getting-started/installation/) for instructions 
on installing uv
## Repository Setup
1) Clone the `bpod_python_overhaul` package
   > `git clone git@github.com:olfactorybehaviorlab/bpod_python_overhaul.git`
2) Navigate into the newly cloned folder
   > `cd ./bpod_python_overhaul/`
3) Initialize and update the three submodules
   > `git submodule init && git submodule update`
4) Create the virtual environment
   > `uv sync --all-packages --extra [PYTHON_PYSIDE_BINDING]`
   > 