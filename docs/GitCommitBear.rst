**GitCommitBear**
=================

Checks the given commit body.

`Supported Languages <../README.rst>`_
-----

* Git

Settings
--------

+---------------------------------+-------------------------------------------------------------+
| Setting                         |  Meaning                                                    |
+=================================+=============================================================+
|                                 |                                                             |
| ``allow_empty_commit_message``  | Whether empty commit messages are allowed or not.           |
|                                 | (Optional, defaults to 'False'.)                            |
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+
|                                 |                                                             |
| ``body_line_length``            | The maximum line-length of the body. The newline character  |
|                                 | at each line end does not count to the length. (Optional,   |
|                                 | defaults to '72'.)                                          |
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+
|                                 |                                                             |
| ``force_body``                  | Whether a body shall exist or not. (Optional, defaults to   |
|                                 | 'False'.)                                                   |
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+
|                                 |                                                             |
| ``shortlog_imperative_check``   | No description given. (Optional, defaults to 'True'.)       +
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+
|                                 |                                                             |
| ``shortlog_length``             | The maximum length of the shortlog. The newline character   |
|                                 | at end does not count to the length. (Optional, defaults to |
|                                 | '50'.)                                                      |
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+
|                                 |                                                             |
| ``shortlog_regex``              | No description given. (Optional, defaults to ''.)           +
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+
|                                 |                                                             |
| ``shortlog_trailing_period``    | Whether a dot shall be enforced at end end or not (or       |
|                                 | ``None`` for "don't care"). (Optional, defaults to 'None'.) |
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+
|                                 |                                                             |
| ``shortlog_wip_check``          | Whether a "WIP" in the shortlog text should yield a result  |
|                                 | or not. (Optional, defaults to 'True'.)                     |
|                                 |                                                             |
+---------------------------------+-------------------------------------------------------------+


Can Detect
----------

* Formatting

License
-------

AGPL-3.0

Authors
-------

* The coala developers (coala-devel@googlegroups.com)
