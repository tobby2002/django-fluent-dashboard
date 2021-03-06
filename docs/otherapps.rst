.. _otherapps:

Other related applications
==========================

The following packages provide additional modules,
which can be displayed at the dashboard:

django-admin-tools
------------------

Invaluable to forget, the `django-admin-tools` package also provides modules for:

* A bookmarks menu
* RSS feed module
* Tab grouping module
* Link list module

Website: https://github.com/django-admin-tools/django-admin-tools

django-admin-user-stats
-----------------------

The `django-admin-user-stats` package adds graphs to the dashboard,
to see the number of registered users in the last month.

Website: https://github.com/kmike/django-admin-user-stats

django-admin-tools-stats
------------------------

Derived from `django-admin-user-stats`, this package adds configurable graphs for any model type.
Different model data can be hooked in, for example, new user registrations, number of votes last month, etc..

* Website: https://github.com/Star2Billing/django-admin-tools-stats

.. _dashboardmods:

collowayproject/dashboardmods
-----------------------------

Initiated by the The Washington Times, this package adds status modules to the admin dashboard for:

* Varnish
* Memcached

When the ``dashboardmods`` package is installed, and added to the ``INSTALLED_APPS``,
the :class:`~fluent_dashboard.dashboard.FluentIndexDashboard` and :class:`~fluent_dashboard.modules.CacheStatusGroup`
classed will automatically pick it up to display the cache status.

Website: https://github.com/callowayproject/dashboardmods

