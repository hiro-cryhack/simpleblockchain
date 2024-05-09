Run the following command to build and upload the project to PyPI:

python setup.py sdist bdist_wheel
pip install twine
twine upload dist/*


Users can use pip to install projects:

pip install simpleblockchain
