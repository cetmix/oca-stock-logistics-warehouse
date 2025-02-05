======================
Stock Measuring Device
======================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:a4ec9dcffcdb9a14e9f8a0633363186a3ac86ae04a2353b96ab977b601314ae4
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Alpha-red.png
    :target: https://odoo-community.org/page/development-status
    :alt: Alpha
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--warehouse-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-warehouse/tree/14.0/stock_measuring_device
    :alt: OCA/stock-logistics-warehouse
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-warehouse-14-0/stock-logistics-warehouse-14-0-stock_measuring_device
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-warehouse&target_branch=14.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

Different manufacturers produce devices which are able to measure and weigh
packages and parcels. Each brand has a different communication protocol. This
module provides an framework to interface such devices with Odoo.

.. IMPORTANT::
   This is an alpha version, the data model and design can change at any time without warning.
   Only for development or testing purpose, do not use in production.
   `More details on development status <https://odoo-community.org/page/development-status>`_

**Table of contents**

.. contents::
   :local:

Installation
============

This module by itself does not do anything.

You will need to install a module implementing the communication with your
device. Look for modules with a name starting with stock_measuring_device.

Configuration
=============

The first step is to configure the Packaging Types (Pallet, Box, ...) in Inventory > Configuration > Product Packaging Types.

Configure the measuring device in Inventory > Configuration > Measuring
Devices, don't forget to set the device type, and any other additional
parameters.

Usage
=====

Use the "Wizard" button on a Measuring Device to open the screen and take
measurements.

Known issues / Roadmap
======================

* The UI could get some improvements
* Being able to open the measurement screen from a product would be nice

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-warehouse/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-warehouse/issues/new?body=module:%20stock_measuring_device%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Camptocamp

Contributors
~~~~~~~~~~~~

* Patrick Tombez <patrick.tombez@camptocamp.com>
* Alexandre Fayolle <alexandre.fayolle@camptocamp.com>
* Carlos Serra Toro <carlos.serra@camptocamp.com>
* `Trobz <https://trobz.com>`_:
    * Hai Lang <hailn@trobz.com>

Other credits
~~~~~~~~~~~~~

The migration of this module from 13.0 to 14.0 was financially supported by Camptocamp

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-gurneyalex| image:: https://github.com/gurneyalex.png?size=40px
    :target: https://github.com/gurneyalex
    :alt: gurneyalex

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-gurneyalex| 

This module is part of the `OCA/stock-logistics-warehouse <https://github.com/OCA/stock-logistics-warehouse/tree/14.0/stock_measuring_device>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
