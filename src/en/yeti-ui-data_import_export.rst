
.. _data_import_export:

============================
Import & Export Data in Yeti
============================

Import & Export Data in Yeti are useful tools for organizing transparent migration from/to an alternative software platform.

Export
~~~~~~

Export of data in Yeti is available from any :ref:`List of Objects <type_of_controls-listofobjects>` control.
You can download all data from the table in the comma-separated values format by clicking on **CSV** link that is usually located at the bottom scrolling line together with information about general amount of objects that were displayed in the :ref:`List of Objects <type_of_controls-listofobjects>` control.


Import: General principles
~~~~~~~~~~~~~~~~~~~~~~~~~~

Import of data in Yeti is available from Working Areas (by pressing *Import* button that is placed on *General management line*) of following sections:

    -   :ref:`Contractors <contractors>`;
    -   :ref:`Accounts <_accounts>`;
    -   :ref:`Gateway Groups <gateway_groups>`;
    -   :ref:`Gateways <gateways>`;
    -   :ref:`Disconnect Policies <disconnect_policy>`;
    -   :ref:`Equipment Registrations <registrations>`;
    -   :ref:`Customer Auths <customer_auth>`;
    -   :ref:`Rateplans <rateplans>`;
    -   :ref:`Destinations <destinations>`;
    -   :ref:`Routing Groups <routing_group>`;
    -   :ref:`Dialpeers <dialpeers>`;
    -   :ref:`Numberlists <numberlists>`;
    -   :ref:`Numberlists items <numberlist_items>`.


:ref:`Form for entering information <type_of_controls-formforentering>` for Import of data consists from two sections: *CSV options* and *Import*.

*CSV options* includes three textual input fields:

    -   *Col sep*    -  character (or string) that is used to separate columns within the importing CSV (comma-separated values) file. For example comma (,) could be used as *Col sep* value. In this case following text: "1,2,3" will be imported as values of three different columns (first column - 1,  second column - 2, third column - 3);
    -   *Row sep*    -  character (or string) that is used to separate rows within the importing CSV (comma-separated values) file;
    -   *Quote char* -  character (or string) that is used to limit some values within the importing CSV (comma-separated values) file. These characters will be removed during the import process and values without these characters will be imported.

**TODO** - finalize and check if it possible to use strings.

Export & Import: Format of the fields for different objects
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**TODO**