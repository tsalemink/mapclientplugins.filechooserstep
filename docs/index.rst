MAP Client Plugin - File Chooser
================================

The **File Chooser** is MAP Client plugin for choosing a file from a location outside the workflow.

.. _fig-mcp-file-chooser-un-configured-step:

.. figure:: _images/un-configured-step.png
   :alt: Un-configured step icon

   An un-configured *File Chooser* step icon.

Configure
---------

This step is used for choosing a file on the local disk from outside the workflow directory.
This step provides a *http://physiomeproject.org/workflow/1.0/rdf-schema#file_location* to define the location where the file is on the local disk.
To choose the file use the *...* button to open a file chooser dialog.
The *File* input is used to hold the relative path from the workflow to the input file location.

.. _fig-mcp-file-chooser-configure-dialog:

.. figure:: _images/step-configuration-dialog.png
   :alt: Step configure dialog

   *File Chooser* step configuration dialog.

Ports
-----

This plugin:

* **provides**:

  * *http://physiomeproject.org/workflow/1.0/rdf-schema#file_location*
