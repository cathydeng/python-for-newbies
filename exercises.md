# Exercises

These exercises go along with [these slides](http://bit.ly/python-for-newbies)

### A. Make sure you have Python
To see what version of Python you have:
```
python --version
```
To see where Python is installed:
```
which python
```

### B. Download this code
The easiest way to do this is with git (git is not the same thing as GitHub).

At the command line, type:
```
git clone https://github.com/cathydeng/python-for-newbies.git
cd python-for-newbies
```
Now you have all these files locally!

### C. Install requirements
To see the packages you have installed:
```
pip freeze
```
To install everything in the `requirements.txt` file:
```
pip install -r requirements.txt
```

### D. Use the Python interactive shell
To get into the interactive shell:
```
python
```
Now you should see `>>>` at the beginning of each line. Here, you can type Python code & see output. For example:
```
my_name = 'Cathy'
'{} is learning Python!!'.format(my_name)
```
To get out of the interactive shell:
```
exit()
```

### E. Run a python script
The interactive shell is useful for testing things out, but not for putting together tasks that you can re-run.

To run the example Python script:
```
python example_python_script.py
```
