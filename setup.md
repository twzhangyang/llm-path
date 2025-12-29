## Create Python Virtual Environment and Install Dependencies
### Setup Python Virtual Environment
```
brew install uv
python3 -m venv .ven && source .ven/bin/activate
which python
python3 -m pip install uv
```

### Activate Virtual Environment
```
source .venv/Scripts/activate
deactivate
```

### Install Required Packages
```
uv pip install torch
uv pip install -r requirements.txt
```

### Start Jupyter Notebook
```
jupyter lab
```