Changelog
---------

2.0.1.dev0
~~~~~~~~~~

* Option to choose if the invoices are exported to Magento on payment or validation (Thanks to Allison Miller)
* Allow to define a prefix for the name of the imported sales orders (Thanks to Augustin Cisterne-Kaas)


2.1.0 (2013.08.05)
~~~~~~~~~~~~~~~~~~

* Import of partners reviewed according to https://launchpad.net/bugs/1193281
  Especially to handle the b2b use cases better.
* Fix: Magento bindings duplicated with the "copy" method (https://launchpad.net/bugs/1205239)
* Fix: 503 Service unavailable protocol error should be retried later (https://launchpad.net/bugs/1194733)
* Fix: Import of guest orders (https://bugs.launchpad.net/openerp-connector/+bug/1193239)
* 'Authorized' import rules to be able to import sales orders authorized by a payment institute but not paid yet. (Thanks to Brendan Clune)
* Define the partners relationships only on the creation of new records, allowing manual specification of company / contact relationships within OpenERP (Thanks to Brendan Clune)
* Fix: State information for partners not mapped correctly (Thanks to Brendan Clune) (https://launchpad.net/bugs/1183837)
* Many others: see the bazaar logs

2.0.0
~~~~~

* First release


..
  Model:
  2.0.1 (date of release)
  ~~~~~~~~~~~~~~~~~~~~~~~

  * change 1
  * change 2
