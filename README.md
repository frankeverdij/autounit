# Autounit.py

This Python script performs several functions for JemJive software:
* Builds within the JemJive framework
* Execution
* Generating Sphinx documentation
* unittests

The unittests are performed by executing the program and comparing results with archived reference data. It uses the **numdiff** program to fuzzy-match floating point numbers by using absolute or relative tolerances.
