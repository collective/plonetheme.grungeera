====================
plonetheme.grungeera
====================

A Diazo_ theme to make the `GrungeEra`_ theme from freelayoutsworld.com easily available in `Plone`_.


Introduction
============

*plonetheme.grungeera* package is an installable Plone_ Theme using the **theming** and **packaging** 
features available in `plone.app.theming`_ to make the `Styleshout`_ theme `GrungeEra`_ easily
available in `Plone`_.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/collective/plonetheme.grungeera/raw/master/plonetheme/grungeera/theme/grungeera/preview.png


Features
========

- It's an installable Plone_ Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo_ package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Add Plone site
--------------

Install Plone 4.x with `plone.app.theming`_ and create a Plone site (if you have not already)
with Diazo theming configured.

.. image:: https://github.com/collective/plonetheme.grungeera/raw/master/docs/screenshot2.png


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.grungeera`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.grungeera


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.grungeera',
    ],


Zip file
--------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download a `zip file <https://github.com/collective/plonetheme.grungeera/raw/master/grungeera.zip>`_.
2. Import the theme from the Diazo theme control panel.

.. image:: https://github.com/collective/plonetheme.grungeera/raw/master/docs/screenshot4.png


Enabling the theme
^^^^^^^^^^^^^^^^^^

Browse to ``http://yoursite/Plone/@@theming-controlpanel`` click on ``Enable`` on ``Plonetheme GrungeEra`` theme from the Diazo control panel. That's it!


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.grungeera/issues
- Source Code: https://github.com/collective/plonetheme.grungeera


Help
----

Obviously there is more work to be done. If you want to help, pull requests accepted! Some ideas:

* Add a diazo rule to import Plone editing styles
* Configure styles to use portal_css
* Improve styles


License
=======

The author is not a "license guy", but the GrungeEra theme is distributed via CC 3.0 license [1]_ and this package is GPL version 2 (assuming that makes sense).

.. [1] http://www.styleshout.com/about.php#license

Credits
-------

- Giacomo Spettoli, (giacomo.spettoli at gmail dot com).
- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).

.. _`Plone`: http://plone.org
.. _`GrungeEra`: http://www.styleshout.com/templates/preview/GrungeEra11/index.html
.. _`Styleshout`: http://www.styleshout.com/
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`Diazo`: http://diazo.org
