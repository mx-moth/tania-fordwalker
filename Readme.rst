======================================
Static site build for Tania Fordwalker
======================================

Development
===========

To build the assets in development:

1. Install `yarn <https://yarnpkg.com/>`_,
2. Install the build requirements::

    $ yarn install

3. Start the development environment::

    $ yarn start

4. Open http://localhost:1234

Production
==========

To compile everything for production, set up the development environment as above, then run::

    $ rm -r dist/
    $ yarn run build

Everything will be compiled to ``dist/``.
