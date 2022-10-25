Usage
=====

.. _installation:

Installation
------------

Bristol, BAU no active project
Bristol, BAU no active project
Civista, in active sales talks, PPP only at this time
Dollar, BAU no active project
Kitsap, active DAO project, but also live with Term/Loc
Pinnacle, PPP only

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

