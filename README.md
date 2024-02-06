# Deadlock Test Suite

This test suite is presented for further testing of the add-on to the static analyzer ___ for analyzing multi-threaded applications in Python with GIL disabled

## Info:
To work with this test suite, you need a version of Python with GIL disabled

[Python 3.9](https://github.com/colesbury/nogil) - Python version with GIL disabled provided by Sam Gross

[PEP 703](https://peps.python.org/pep-0703/) - the article describing problems with disabling GIL


### CWE used:
- [CWE-667: Improper locking](https://cwe.mitre.org/data/definitions/667.html)
- [CWE-833: Deadlock](https://cwe.mitre.org/data/definitions/833.html)

