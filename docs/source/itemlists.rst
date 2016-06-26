Item Lists
==========

The list of items used in the experimental procedure is generated from the item
list files found in the experiment directory (see :ref:`directory_structure`).
This is done every time the experiment is started. Thus it is important to use
the same set of item list files for all subjects in a study.

Item list files
---------------
Item list files are ordinary text files (``.txt``) that can be edited with any
text editor. An item list file must obey the following naming scheme in order to
be recognized and loaded by the experiment::

  itemlist_<name>.txt

The part of the filename between the first underscore and the dot before the
extension is considered the name of the item list.

Example::

  itemlist_office.txt     -->     item list is named 'office'


Item list definition
--------------------
The item list text files define one item per line. Example::

  write invoices
  prepare meeting
  update timetable

:Attention:
  Empty lines in the file lead to items for which nothing is shown on screen. So
  avoid empty lines in the file. Empty lines are often found at the end of a
  file after editing. Use the arrow-down key on the keyboard to move the cursor
  to the end of the file to see if there are any empty lines.
