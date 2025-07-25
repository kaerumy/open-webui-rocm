# OpenWeb UI

openweb-ui with rocm torch backend

This is a fork of the OpenWeb UI project, modified to work with the ROCm
backend for PyTorch. It allows you to run the OpenWeb UI on systems with
AMD GPUs.

It assumes you have a working ROCm installation and uv installed.

## Installation
1. Clone the repository:

```bash
git clone https://github.com/kaerumy/open-webui-rocm
cd open-webui-rocm
```
2. Create a virtual environment:

```bash
uv venv --python 3.11
source .venv/bin/activate
uv pip install open-webui
```

3. To start the server, run:

```source .venv/bin/activate```

Then, run:

```openweb-ui serve```

Data is in .venv/lib/python3.11/site-packages/open_webui/data
