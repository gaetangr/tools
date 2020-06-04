## Tools used for formating code
Just copy/paste into your code, they will run one after the other

    isort -rc .
    
    docformatter --recursive --in-place .

    black --line-length 79 -t py37 -S .

    flake8 -rc .
    
 ## Informations about the modules
   
- **Isort** : Isort your python imports for you so you don’t have to.
- **Docformatter** : Docformatter currently automatically formats docstrings to follow a subset of the PEP 257 conventions
- **Black** : Black is the uncompromising Python code formatter.
- **Flake8** : The modular source code checker
