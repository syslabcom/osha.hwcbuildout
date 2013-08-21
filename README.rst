osha.hwcbuildout
================

Buildout for OSHA HWC


Installing
==========

Create a buildout.cfg, extending the environment you want,
production.cfg, development.cfg etc::

    [buildout]
    extends = profiles/development.cfg

Bootstrap the buildout::

    python2.7 bootstrap.py

Run the buildout

    ./bin/buildout


License
=======

See LICENSE.EUPL

