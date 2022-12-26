========
Shipping
========

Depending on your shipping strategy, you have the choice to either use your :ref:`own shipping
methods <ecommerce-own-shipping>`, or use an integration with an :ref:`existing shipping provider
<ecommerce-shipping-providers>`.

Own shipping methods
====================

.. _ecommerce-own-shipping:

You can create your own custom shipping methods and define rules to compute shipping costs. To do
so, go to :menuselection:`Website --> Configuration --> Shipping Methods`, and either select an
**existing** shipping method, or :guilabel:`Create` one. When creating a shipping method, you can
choose between
:doc:`Fixed Price </applications/inventory_and_mrp/inventory/shipping/setup/delivery_method>`,
:doc:`Based on Rules </applications/inventory_and_mrp/inventory/shipping/setup/delivery_method>`,
and :guilabel:`Pickup in store`.

Pickup in store
---------------

:guilabel:`Pickup in store` must first be **enabled** in the settings (:menuselection:`Website -->
Configuration --> Settings --> Shipping section)` by checking :guilabel:`On Site Payments &
Picking`. Once enabled, you can select and :guilabel:`Customize Pickup Sites`. The
:guilabel:`Picking sites` are **website-specific**, although the same :guilabel:`picking site` can
be enabled for **multiple** websites.

.. seealso::
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/setup/delivery_method`
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/operation/invoicing`
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/operation/multipack`
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/operation/cancel`

Shipping providers
==================

.. _ecommerce-shipping-providers:

Another solution is to use one of the integration with an existing shipping provider. The advantage
of using an integration is that delivery cost are automatically computed based on each order as well
as generating shipping labels.

.. seealso::
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/setup/third_party_shipper`
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/setup/ups_credentials`
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/setup/dhl_credentials`
   - :doc:`/applications/inventory_and_mrp/inventory/shipping/operation/labels`

Website availability
====================

Shipping methods can be made available on **specific** websites *only*, if desired. To do so, go to
:menuselection:`Website --> Configuration --> Settings --> Shipping Methods`, and select the desired
**shipping method**. In the :guilabel:`Website` field, set the website you want the shipping method
to be restrained to. Leave the field **empty** for the method to be available on *all* websites.

Delivery method at checkout
===========================

Customers can choose the shipping method at the end of the checkout process, at the
:guilabel:`Confirm Order` step.

.. image:: shipping/shipping-checkout.png
   :align: center
   :alt: Delivery method choice at checkout

.. seealso::
   :doc:`../checkout_payment_shipping/checkout`
