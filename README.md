## Commands:
- python setup.py sdist
- pip install twine

### For test pypi
- twine upload --repository-url https://test.pypi.org/legacy/ dist/* 

### For pypi
- twine upload dist/*

### Install package from test pypi
- pip install -i https://test.pypi.org/simple/ distribution-test==1.0

### Install package from pypi
pip install distribution-test