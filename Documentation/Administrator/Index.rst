﻿.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _admin-manual:

Administrator Manual
====================

Target group: **Administrators**

This extension is easy to install and to configure.
There are no dependencies to other extension, only to TYPO3 core.


.. _admin-installation:

Installation
------------

To install the extension, perform the following steps:

#. Install extension via composer
#. Go to the Extension Manager
#. Install the extension
#. Load the static TypoScript template to your site


.. figure:: ../Images/Administrator/extensionmanager.png
   :alt: Extension Manager

   Extension Manager

   Install it in the Extension Manager


.. _admin-configuration:

Configuration
-------------

#. Copy the templates (/Resources/Private/Templates/) and layouts (/Resources/Private/Layouts/) from the extension folder to a folder in your own sitepackage if you want to edit them
#. Configure your new template pathes in TypoScript
#. Include the TypoScript of your sitepackage after the extension template
#. Style the output like you want it


.. _admin-faq:

FAQ
---

Is it possible to use my own templates?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Yes, please copy the templates from the extension to your own folder (e.g. EXT:my_site_package/Resources/Private/Templates/Ext/) and configure the path in the TypoScript of the extension. See also step 1 and 2 in configuration.
