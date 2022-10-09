抖音下拉接口
=====

必要参数
------------
- `username`
- `password`



添加任务（批量或单个）
----------------
URL
`https://www.waimaojingling.com/api/dyxl/addTask?username=&password=&data=`

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

