.. _envvars:

Environment Variables
*********************

.. _env-debug:

``DEBUG``
=========
Set to ``*`` to get a lot of debug information.
See :ref:`debug-usage` for more.


CI
==

See :ref:`automatic-checks`.

.. _env-circleci:

``CIRCLECI``
------------
Used to check if this is a Circle CI environment.

.. _env-frigg:

``FRIGG``
---------
Used to check if this is a Frigg environment.

.. _env-semaphore:

``SEMAPHORE``
-------------
Used to check if this is a Semaphore environment.

.. _env-travis:

``TRAVIS``
----------
Used to check if this is a Travis CI environment.

.. _env-gitlab_ci:

``GITLAB_CI``
-------------
Used to check if this is a GitLab CI environment.

``CI_SERVER_HOST``
------------------
Host component of the GitLab instance URL, without protocol and port.
Example: `gitlab.example.com`

.. note::
  Automatically set in a GitLab CI environment from version 12.1.


Authentication
==============

.. _env-gh_token:

``GH_TOKEN``
------------
A personal access token from GitHub. This is used for authenticating
when pushing tags, publishing releases etc. See :ref:`automatic-github` for
usage.

To generate a token go to https://github.com/settings/tokens
and click on *Personal access token*.

.. _env-gl_token:

``GL_TOKEN``
------------
A personal access token from GitLab. This is used for authenticating
when pushing tags, publishing releases etc.

.. _env-pypi_password:

``PYPI_PASSWORD``
-----------------
Used together with :ref:`env-pypi_username` when publishing to https://pypi.org/.

.. _env-pypi_username:

``PYPI_USERNAME``
-----------------
Used together with :ref:`env-pypi_password` when publishing to https://pypi.org/.

.. note::
  See :ref:`automatic-pypi` for more about PyPI uploads.
