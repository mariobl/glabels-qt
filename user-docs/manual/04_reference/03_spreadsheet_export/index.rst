.. _spreadsheet_export:

Export CSV files from various applications
******************************************

------------------------
Spreadsheet applications
------------------------

.. More options: Microsoft Excel, Collabora Calc …?

LibreOffice Calc
----------------

Choose :menuselection:`File --> Save as…`. In the :guilabel:`Filter` box,
select :guilabel:`Text CSV`. (Optional) Set the field options for the :file:`.csv`
file. Select :guilabel:`Edit filter settings`. In the :guilabel:`Export of text files`
dialog, select the options that you want. Click :guilabel:`OK` and then
:guilabel:`Save`.

Calligra Sheets
---------------

Choose :menuselection:`File --> Export…` or :menuselection:`File --> Save As…`.
The file saver dialog shows the current filename, currently probably with an
:file:`.ods` extension (the default in :application:`Calligra Sheets`). Open the
:guilabel:`File type` drop-down list and choose :guilabel:`CSV document`. The
filename extension changes automatically to :file:`.csv`. Then click on
:guilabel:`Save`.

Google Sheets
-------------

.. Please verify this on ChromeOS; this is the behavior in the web interface

Choose :menuselection:`File --> Download --> Comma Separated Values (CSV)`. The file
will be downloaded automatically into your configured download folder. The
original filename will be suffixed with * - SheetX* where *X* is the number of
the sheet (should usually be irrelevant for our purposes).

Gnumeric
--------

Currently (2026-01), :program:`Gnumeric` seems to have no options to export
:file:`.csv` files. Please correct me if that is indeed possible.

---------------------------------
Mail Clients and PIM Applications
---------------------------------

Mozilla Thunderbird
-------------------

You can export an address book of your choice from :program:`Thunderbird`.
Click on the address book icon in the vertical toolbar on the left or press
:kbd:`Ctrl-2` to open the address book view. Right-click on one of your address books
and choose :guilabel:`Export…`. A file chooser dialog will be opened. On top of
the window you can enter a name and then choose a location for the to be exported
file. With the drop-down menu in the bottom right corner, you can choose a file
type; we need :guilabel:`Comma Separated (UTF-8)` for our purposes. Note, the
exported :file:`.csv` file will contain many header entries which we don't need at
all. It makes sense to open the exported file in a text editor (or even a spreadsheet
application and re-export it as :file:`.csv` file) to remove the unneeded entries.

Evolution
---------

KAddressBook
------------
