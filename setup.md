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
python3 -m pip install ipykernel
python3 -m ipykernel install --user --name=llm-path --display-name "Python (llm-path)"
jupyter lab
```

### How to use it in the UI
- Once Jupyter Lab opens:
- Open your ch02.ipynb.
- Look at the top right corner (it likely says "Python 3 (ipykernel)" or "No Kernel").
- Click that text.
- A "Select Kernel" dialog will appear. Choose "Python (llm-path)" from the dropdown.