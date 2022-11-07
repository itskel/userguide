Transparency
=====

Who is Th3J3st3r?
------------
The Jester is a prolific hactivist and the creator of Counter.Social. He is listed in TIME Magazine's Most Influential People Online and his laptop is exhibited in the International Spy Museum in Washington, DC. Some may have noticed his cameo role in the TV Show, *Mr. Robot*. His alleged escapades can be found covered by NBC, Homeland Security Today, Gizmodo, Newsweek, Tech Insider, and the Larry King Show. 

Visit <https://counter.social/whojay.html for more info. 


How is Counter.Social Funded?
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

