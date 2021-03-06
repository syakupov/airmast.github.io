isotherm_lower
==============

Set isotherm lower value
------------------------

.. class:: request-table-3

+--------------+------------------------------------------+-------------+
| Request Type |                   URL                    | DJI Zenmuse |
+==============+==========================================+=============+
| POST         | **/api/v1/isotherm_lower/**\ ``<value>`` | XT          |
+--------------+------------------------------------------+-------------+

``<value>`` is an integer value of isotherm (from −40 to 1000).

**Note:** This setting takes effect only if isotherm_ is enabled.

.. <html>

.. _isotherm: /camadapter/api/isotherm/

.. </html>

Sample Request
~~~~~~~~~~~~~~

.. code:: http

    POST http://localhost:8123/api/v1/isotherm_lower/90

Sample Response
~~~~~~~~~~~~~~~

Status code: **200**

.. code:: javascript

    {
      "success": true
    }
