Geocoder: Simple JSON
=====================

.. image:: https://badge.fury.io/py/geocoder.png
    :target: http://badge.fury.io/py/geocoder

.. image:: https://travis-ci.org/DenisCarriere/geocoder.png?branch=master
        :target: https://travis-ci.org/DenisCarriere/geocoder


Geocoder is a MIT Licensed Geocoding library, written in Python, 
simple and consistant.

Many online providers such as Google & Bing have geocoding services,
these providers do not include Python libraries and have different 
JSON responses between each other.

Consistant JSON responses from various providers.

.. code-block:: python

    >>> g = geocoder.google('New York City')
    >>> g.latlng
    [40.7127837, -74.0059413]
    >>> g.state
    'New York'
    >>> g.json
    ...

Providers
---------
- ArcGIS ESRI
- Bing
- CanadaPost
- FreeGeoIP
- Geocoder.ca
- Geonames
- Google
- MapQuest
- MaxMind
- Nokia
- OpenCage
- OSM (OpenStreetMap)
- Ottawa (GeoOttawa)
- TomTom
- Yahoo

Features
--------

- GeoJSON Support
- OpenStreetMap Support
- Command Line Interface
- Confidence Score
- Well Known Text Support

Installation
------------

To install Geocoder, simply:

.. code-block:: bash

    $ pip install geocoder


Documentation
-------------

Documentation is available at http://deniscarriere.github.io/geocoder.


Topic not available?
--------------------

If you cannot find a topic you are looking for, please feel free to ask me `@DenisCarriere`_ or post them on the `Github Issues Page`_.

Support
-------

This project is free & open source, it would help greatly for you guys reading this to contribute, here are some of the ways that you can help make this Python Geocoder better.

Feedback
--------

Please feel free to give any feedback on this module. If you find any bugs or any enhancements to recommend please send some of your comments/suggestions to the `Github Issues Page`_.

Twitter
-------

Speak up on Twitter `@DenisCarriere`_ and tell me how you use this Python Geocoder. New updates will be pushed to Twitter Hashtags `#geocoder`_.

Thanks to
---------

A big thanks to all the people that help contribute: 

* `@flebel <https://github.com/flebel>`_
* `@patrickyan <https://github.com/patrickyan>`_
* `@themiurgo <https://github.com/themiurgo>`_
* `@esy <https://github.com/lambda-conspiracy>`_


.. _`@DenisCarriere`: https://twitter.com/DenisCarriere
.. _`#geocoder`: https://twitter.com/search?q=%23geocoder
.. _`Github Issues Page`: https://github.com/DenisCarriere/geocoder/issues
