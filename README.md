# Tán công trùng tu

## Setup

```bash
pyenv install 3.10.11  # install
pyenv global 3.10.11  # set default
```

```bash
export PYTHONPATH=$PYTHONPATH:$PWD
python3 -m venv venv  # recommend using Python 3.10
source venv/bin/activate  # on Windows: venv\Scripts\activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
pre-commit install
pre-commit autoupdate
```