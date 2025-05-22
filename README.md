# PyLibTestLib

## Folder structure
```
your_library/
├── your_library/
│   ├── __init__.py
│   └── core.py       # your main code
├── tests/
│   └── test_core.py
├── setup.py          # (either setup.py or pyproject.toml)
├── README.md
├── LICENSE
└── pyproject.toml    # (optional but modern)
```
### pyproject.toml and setup.py precedence
pyproject.toml and setup.py are both configurations for the library.<br>
pyproject.toml will take effect over setup.py if it is present.<br>
Use pyproject.toml unless working with legacy config<br>

## Installation
pip install git+https://github.com/PreDated92/PyLibTestLib

### From local
```
cd your-local-repo
pip install -e .
```

## Uninstall
pip uninstall PyLibTestLib
