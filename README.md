# Req

* Python 3

* Cuenta en pypi test

* Cuenta en pypi

* pip install twine

* pip install wheel

* Estructura 

# Librería-base
* setup.py
* README.md
# librería
* __init__.py
* x.py

# instrucciones

* En el terminal 

* python setup.py sdist bdist_wheel

* twine upload --repository testpypi dist/nombre-version.tar.gz dist/nombre-version-py3-none-any.whl

* Google colab para comprobar si funciona

# Definitiva a pypi

* twine upload dist/nombre-version.tar.gz dist/nombre-version-py3-none-any.whl
