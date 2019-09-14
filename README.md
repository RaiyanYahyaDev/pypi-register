A quick way to book and reserve your package name on pypi. Edit the setup.py file and fill in the neccesary details. 
You need to have twine locally installed and configured and an account on Pypi.

```
python setup.py bdist_wheel upload
```

```
twine upload dist/*
```

Please use this effectively and do not go reserving package names. Do good and use with responsibilty !!