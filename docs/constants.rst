Constants
=========

Kucoin defines constants for Redord Types, Order Side, Order Status and Resolution. These are accessible from the Client class.

.. code:: python

    RECORD_WITHDRAWAL = 'WITHDRAW'
    RECORD_DEPOSIT = 'DEPOSIT'

    SIDE_BUY = 'BUY'
    SIDE_SELL = 'SELL'

    TRANSFER_STATUS_SUCCESS = 'SUCCESS'
    TRANSFER_STATUS_CANCELLED = 'CANCEL'

    # Kucoin has 2 kline endpoint and they have been setup to take the below values

    RESOLUTION_1MINUTE = '1'
    RESOLUTION_5MINUTES = '5'
    RESOLUTION_15MINUTES = '15'
    RESOLUTION_30MINUTES = '30'
    RESOLUTION_1HOUR = '60'
    RESOLUTION_8HOURS = '480'
    RESOLUTION_1DAY = 'D'
    RESOLUTION_1WEEK = 'W'

Use in your code like below.

.. code:: python

    from kucoin.client import Client

    order_side = Client.SIDE_BUY
