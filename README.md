# Setup

## Python
```bash
brew install python3
```

## Virtual Environment

### Install virtualenv and wrapper
```bash
pip3 install virtualenv virtualenvwrapper
```

### Put this in .bashrc or .zshrc
```bash
source /usr/local/bin/virtualenvwrapper.sh
export WORKON_HOME=$HOME/.virtualenvs
```

### Create and workon virtualenv
```bash
mkvirtualenv ml
workon ml
```

## Python packages

### Install
```bash
pip3 install -r requirements.txt
```

### Verification
```bash
python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"
```
