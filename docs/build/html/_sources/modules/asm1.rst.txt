ASM1 reactor module
===================

Import
------

.. code-block:: python

   from asm1model import asm1

Class
-----

``ASM1(XINIT1, PAR1, VOL1, SOSAT1, TEMPMODEL, ACTIVATE, DECAY)``

Parameters
----------

- ``XINIT1``: initial ASM1 state vector
- ``PAR1``: ASM1 parameter vector
- ``VOL1``: reactor volume
- ``SOSAT1``: oxygen saturation value
- ``TEMPMODEL``: temperature model flag
- ``ACTIVATE``: dummy-state activation flag
- ``DECAY``: decay-mode flag

Notes
-----

This page documents the module-level interface intended for future flowsheet construction.
