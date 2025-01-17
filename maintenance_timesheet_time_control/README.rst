===================================
Maintenance Timesheets Time Control
===================================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fmaintenance-lightgray.png?logo=github
    :target: https://github.com/OCA/maintenance/tree/14.0/maintenance_timesheet_time_control
    :alt: OCA/maintenance
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/maintenance-14-0/maintenance-14-0-maintenance_timesheet_time_control
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/240/14.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

It allows to track the exact moment when a timesheet line is started (not only
the day, but also the minute and second) and let users start and stop timers
easily.

**Table of contents**

.. contents::
   :local:

Installation
============

This module is auto-installed when ``maintenance_timesheet`` and ``project_timesheet_time_control`` are
installed.

This module depends on modules found in these repositories:

* `OCA/timesheet <https://github.com/OCA/timesheet>`__
* `OCA/web <https://github.com/OCA/web>`__
* `OCA/project <https://github.com/OCA/project>`__

Usage
=====

In general the usage instructions from ``project_timesheet_time_control`` apply with the following additions.

Via maintenance requests:

#. Go to *Maintenance > Maintenance > Maintenance Requests*.
#. If a request has a running timesheet line, it will display a *Stop* button.
#. Other requests that have enabled timesheets will display a *Start* button
   that will open the same wizard as the timesheet lines, duplicating task's
   last timesheet line.
#. You can see the same in list view.
#. Click on any existing request or create a new one.
#. You can see the same feature in the action buttons box.

Note: All the *Start/Resume/Stop* features are disabled if you don't belong to
the *Timesheets/User* group or if you are viewing a timesheet that belongs
to another user.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/maintenance/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/maintenance/issues/new?body=module:%20maintenance_timesheet_time_control%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Tecnativa

Contributors
~~~~~~~~~~~~

* `Tecnativa <https://www.tecnativa.com>`_:

  * Víctor Martínez
  * Pedro M. Baeza

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-victoralmau| image:: https://github.com/victoralmau.png?size=40px
    :target: https://github.com/victoralmau
    :alt: victoralmau

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-victoralmau| 

This module is part of the `OCA/maintenance <https://github.com/OCA/maintenance/tree/14.0/maintenance_timesheet_time_control>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
