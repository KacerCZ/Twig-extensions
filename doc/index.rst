Twig Extensions
===============

.. toctree::
    :hidden:

    text
    i18n
    intl
    array
    date
    gettext

The Twig Extensions is a library that provides several useful extensions
for Twig. You can find it's code at `GitHub.com/twigphp/Twig-extensions`_.

.. _extensions-install:

Installation
------------

This library can be installed via Composer running the following from the
command line:

.. code-block:: bash

    composer require twig/extensions

* :doc:`Text <text>`: Provides useful filters for text manipulation;

* :doc:`I18n <i18n>`: Adds internationalization support via the ``gettext``
  library;

* :doc:`Intl <intl>`: Adds a filter for localization of ``DateTime`` objects;

* :doc:`Array <array>`: Provides useful filters for array manipulation;

* :doc:`Date <date>`: Adds a filter for rendering the difference between dates;

* :doc:`Gettext <gettext>`: Adds a complete interface for the ``gettext`` extension,
  including automated native string extraction.

.. _`GitHub.com/twigphp/Twig-extensions`: https://github.com/twigphp/Twig-extensions
