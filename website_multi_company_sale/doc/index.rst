==========================================
 Real Multi Website (eCommerce extension)
==========================================

Installation
============

* `Install <https://odoo-development.readthedocs.io/en/latest/odoo/usage/install-module.html>`__ this module in a usual way

Configuration
=============

Follow instruction of the base module `Real Multi Website <https://www.odoo.com/apps/modules/11.0/website_multi_company/>`__.

Website Orders
--------------

* Open menu ``[[ Website ]] >> Configuration >> Websites``
* For each website configure **Salesperson** and **Sales Channel** fields
* RESULT: new orders made via website will be assigned to proper Salesperson and Sales Channel

Multi-categories
----------------

* Open menu ``[[ Website ]] >> Configuration >> Products >> eCommerce Categories``
* Specify **Websites** fields to parent categories.
* Open shop at some of your website
* Login as Administrator
* In ``Customize`` section activate ``[x] eCommerce Categories``
* RESULT: parent categories for current website and categories without value at **Websites** fields are shown only. **Websites** value of child categories are ignored.
