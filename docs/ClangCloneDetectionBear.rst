**ClangCloneDetectionBear**
===========================

Checks the given code for similar functions that are probably redundant.

`Supported Languages <../README.rst>`_
-----

* C
* C++
* CUDA
* Objective-C
* Objective-C++
* OpenCL
* OpenMP

Settings
--------

+---------------------------+--------------------------------------------------------+
| Setting                   |  Meaning                                               |
+===========================+========================================================+
|                           |                                                        |
| ``max_clone_difference``  | The maximum difference a clone should have. (Optional, |
|                           | defaults to '0.185'.)                                  |
|                           |                                                        |
+---------------------------+--------------------------------------------------------+


Can Detect
----------

* Duplication