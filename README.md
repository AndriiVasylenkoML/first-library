# first library
Python library, albeit for your team at work or for some open source project online.

1. Create a virtual environment for your folder:  
```python3 -m venv venv```   
```source venv/bin/activate```

2. Execute all tests stored in the ‘tests’ folder:  
```python setup.py pytest```

3. make sure you have pip installed wheel, setuptools and twine:  
```pip install wheel setuptools twine```

4. Create content for your library:  
`pip install pytest==4.4.1`  
`pip install pytest-runner==4.4`

5. Build your library:  
```python setup.py pytest```  
```pip install /path/to/wheelfile.whl```
### Source: 
- https://medium.com/analytics-vidhya/how-to-create-a-python-library-7d5aea80cc3f
