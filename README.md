# Deadlock Test Suite

This test suite is presented for further testing of the add-on to the static analyzer ___ for analyzing multi-threaded applications in Python with GIL disabled

## Info:
To work with this test suite, you need a version of Python with GIL disabled

[Python 3.9](https://github.com/colesbury/nogil) - Python version with GIL disabled provided by Sam Gross

[PEP 703](https://peps.python.org/pep-0703/) - the article describing problems with disabling GIL


### CWE used:
- [CWE-667: Improper locking](https://cwe.mitre.org/data/definitions/667.html)
- [CWE-833: Deadlock](https://cwe.mitre.org/data/definitions/833.html)

### Environment:
You need to install [pyenv](https://github.com/pyenv/pyenv?tab=readme-ov-file#installation) and python-nogil via this command:
```
pyenv install nogil-3.9.10-1
```
Switch python3 to nogil-3.9.10-1:
```
pyenv local nogil-3.9.10-1 
```
### Running tests:
And all that's left to do is run this:
```
python3 main.py 
```
