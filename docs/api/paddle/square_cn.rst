.. _cn_api_fluid_layers_square:

square
-------------------------------

.. py:function:: paddle.square(x,name=None)




该OP执行逐元素取平方运算。

.. math::
    out = x^2

参数
::::::::::::

    - **x** (Tensor) - 任意维度的Tensor，支持的数据类型： float32，float64。
    - **name** (str，可选) - 具体用法请参见 :ref:`api_guide_Name` ，一般无需设置，默认值为None。

返回
::::::::::::
取平方后的Tensor，维度和数据类型同输入一致。

代码示例
::::::::::::

.. code-block:: python

	import paddle

	x = paddle.rand(shape=[32, 784])
	y = paddle.square(x)
	print(y.shape)







