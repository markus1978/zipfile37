This is a backport of the zipfile module from Python 3.6, which contains some
improvements.

Suggested usage:

.. code:: python

    if sys.version_info >= (3, 6):
        import zipfile
    else:
        import zipfile36 as zipfile
