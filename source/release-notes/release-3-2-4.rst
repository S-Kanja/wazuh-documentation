.. Copyright (C) 2022 Wazuh, Inc.

.. meta::
  :description: Wazuh 3.2.4 has been released. Check out our release notes to discover the changes and additions of this release.
.. _release_3_2_4:

3.2.4 Release notes
===================

This section shows the most relevant improvements and fixes in version 3.2.4. More details about these changes are provided in each component changelog.

- `wazuh/wazuh <https://github.com/wazuh/wazuh/blob/v3.2.4/CHANGELOG.md>`_
- `wazuh/wazuh-api <https://github.com/wazuh/wazuh-api/blob/v3.2.4/CHANGELOG.md>`_
- `wazuh/wazuh-ruleset <https://github.com/wazuh/wazuh-ruleset/blob/v3.2.4/CHANGELOG.md>`_
- `wazuh/wazuh-kibana-app <https://github.com/wazuh/wazuh-kibana-app/blob/v3.2.4-6.2.4/CHANGELOG.md>`_
- `wazuh/wazuh-kibana-splunk <https://github.com/wazuh/wazuh-splunk/blob/v3.2.4-7.1.1/CHANGELOG.md>`_

Wazuh minor fixes
-----------------

Most of the bug fixes in this release are fairly minor, but a few fixes deserve special mention:

 - ``<queue_size>`` setting was not properly parsed by ``maild`` causing the termination of the process.
 - Python 3 incompatibilities in the framework that may affect the correct behavior of the cluster.

Wazuh app for Splunk
--------------------

This release includes:

 - New GDPR tab.
 - Multi-API support.
 - Multi-index support.
 - Several performance improvements and bug fixes.


Wazuh app for Kibana
--------------------

Relevant changes in the Wazuh app are:

 - New reporting feature: Generate reports from Overview and Agents tab.
 - New check included to warn about systems with low RAM (less than 3GB).
 - Several performance improvements and bug fixes.
