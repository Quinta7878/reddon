https://semutaspal.com/gambar-bunga/
https://semutaspal.com/gambar-pemandangan/
https://semutaspal.com/translate-bahasa-jawa/
https://semutaspal.com/translate-bahasa-bali/
https://semutaspal.com/translate-bahasa-sunda/
https://semutaspal.com/translate-bahasa-korea/
https://semutaspal.com/translate-aksara-jawa/
https://semutaspal.com/translate-aksara-bali/
https://semutaspal.com/translate-aksara-sunda/
https://semutaspal.com/translate-huruf-hangul/
https://semutaspal.com/asean/
https://semutaspal.com/iklan/

https://bit.ly/3STPBYh
https://bit.ly/49tLckr
https://bit.ly/49tKXWl

Usage
=====

.. _installation:

Installation
------------

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

