# local dev environment, make sure python 3.10+ is installed

### create virtual environment

```py
python3 -m venv venv
# or 
python -m venv venv
```

### activate the virtual environment

macOS/Linux:

```bash
source venv/bin/activate
```

Windows (Command Prompt):

```shell
.\\venv\\Scripts\\activate.bat
```

Windows (PowerShell):

```shell
.\\venv\\Scripts\\Activate.ps1
```

## after that make sure you are inside (venv) in terminal, then

### 1 install requirements using

```bash
pip install -r requirements.txt
```

### 2 run docs using

```bash
mkdocs serve
```

## quick utility commands

to clean up __pycache__, make sure to stage ur changes before running the command

```bash
find . -name "__pycache__" -type d -exec rm -r {} +

```

to exit the virtual environment, simply run:

```bash
deactivate
```

the terminal prompt will return to its normal state.
