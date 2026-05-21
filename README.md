# brain-alignment

## Install uv
- MacOS/Linux: curl -LsSf https://astral.sh/uv/install.sh | sh or pip install uv
- windows: powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

## install the dependencies and activate the environment
uv sync

source .venv/bin/activate

## install pip and ipykernels
uv add pip
python -m pip install ipykernel -U --force-reinstall

## Finally run the notebook
