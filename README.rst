*****************
Mopidy-Syncprojects
*****************

.. image:: https://img.shields.io/pypi/v/Mopidy-Syncprojects
    :target: https://pypi.org/project/Mopidy-Syncprojects/
    :alt: Latest PyPI version

<!--
.. image:: https://img.shields.io/github/workflow/status/mopidy/mopidy-syncprojects/CI
    :target: https://github.com/mopidy/mopidy-syncprojects/actions
    :alt: CI build status

.. image:: https://img.shields.io/codecov/c/gh/mopidy/mopidy-syncprojects
    :target: https://codecov.io/gh/mopidy/mopidy-syncprojects
    :alt: Test coverage
-->

`Mopidy <https://mopidy.com/>`_ extension for playing music from
`Syncprojects <https://github.com/k3an3/syncprojects-web>`_.

Forked from [Mopidy-SoundCloud](https://github.com/mopidy/mopidy-soundcloud)


Installation
============

Install by running::

    sudo python3 -m pip install Mopidy-Syncprojects


Configuration
=============

#. You must have a user account with Syncprojects (not open to general public yet) 

#. You need a SyncProjects authentication token

#. Add the authentication token to the ``mopidy.conf`` config file::

    [syncprojects]
    auth_token = 1-1111-1111111


Troubleshooting
===============

Open an issue...

Credits
=======

- Original author of Mopidy-SoundCloud: `Janez Troha <https://github.com/dz0ny>`_
- Mopidy-SoundCloud `Contributors <https://github.com/mopidy/mopidy-soundcloud/graphs/contributors>`_
