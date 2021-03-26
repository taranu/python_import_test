# python_import_test
Python nested package for testing IDE imports

To test that the structure works, clone and run:

PYTHONPATH=$PYTHONPATH:$PWD/python_import_test/pyimpt_import:$PWD/python_import_test/pyimpt_sub1/python:$PWD/python_import_test/pyimpt_sub2/python:$PWD/python_import_test/pyimpt_sub2_subsub2/python python python_import_test/userpkg_pyimpt/import_test.py

To test on PyCharm (for example):

PYTHONPATH=$PYTHONPATH:$PWD/python_import_test/pyimpt_import:$PWD/python_import_test/pyimpt_sub1/python:$PWD/python_import_test/pyimpt_sub2/python:$PWD/python_import_test/pyimpt_sub2_subsub2/python pycharm > pycharm.log 2>pycharm.err &