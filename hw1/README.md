To get your system up-to-date with CS 287 requirements, make sure you 
first have conda and pip installed.  Then, create a new virtual 
environment for the course called ``cs287`` with the following command:
```
conda create -n cs287 python=3.8
```

Then, download the ``requirements.txt`` file, put it in your root 
directory and run the following command:
```
pip install -r requirements.txt 
```

This should download a bunch of packages that will be used in the 
course.  To check that the correct versions were downloaded, do the 
following:
```
conda activate cs287
python
```
This will open up a local Python interpreter.  Then, try
```python
import torch
print(torch.__version__)
```
If the output is either ``'1.8.1'`` or ``'1.8.0'``, then you are set!
