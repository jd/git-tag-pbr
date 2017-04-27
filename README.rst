`git-tag-pbr` is a simple program to automate the tagging of release of
software using `pbr`_.

=======
 Usage
=======

Simply run::

    $ git tag-pbr

The version will be automatically computed based on the output of `python
setup.py --version`. This therefore makes usage of `Sem-Ver` pseudo-headers in
commit messages as `described in pbr documentation
<https://docs.openstack.org/developer/pbr/#version>`_.

You can override the version number by passing it a version as argument::

    $ git tag-pbr 1.2.3

.. _pbr: https://pypi.python.org/pypi/pbr
