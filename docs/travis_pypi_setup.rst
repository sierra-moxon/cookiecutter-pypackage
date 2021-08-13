
Your Release Process
--------------------

If you are using this feature, this is how you would do a patch release:

.. code-block:: bash

    bump2version patch
    git push --tags

This will result in:

* mypackage 0.1.1 showing up in your GitHub tags/releases page
* mypackage 0.1.1 getting released on PyPI

You can also replace patch with `minor` or `major`.

