:orphan:

.. Auto-generated by help-rst from "mirtk average-overlap -h" output

average-overlap
===============

.. program:: average-overlap


Synopsis
--------

::

    average-overlap [-h] [--micro] [--measure MEASURE [MEASURE ...]]
    [--segment NAME LABEL... [NAME LABEL... ...]]
    [--noheader] [--noid] [--output OUTPUT]
    tables [tables ...]


Description
-----------

.. include:: _descriptions/average-overlap.rst



Arguments
---------

.. option:: tables

   List of CSV files written by evaluate-overlap -table
   option.


Command options
---------------

.. option:: -h, --help

   show this help message and exit

.. option:: --micro, -micro

   Compute micro-average of each measure instead of a
   macro-average.

.. option:: --measure MEASURE [MEASURE ...], -measure MEASURE [MEASURE ...], --metric MEASURE [MEASURE ...], -metric MEASURE [MEASURE ...]

   Overlap measure(s) to include in output, all by
   default.

.. option:: --segment NAME LABEL... [NAME LABEL... ...], -segment NAME LABEL... [NAME LABEL... ...]

   Average the overlap measures for the specified labels,
   LABEL must be integer or range '5..10'.

.. option:: --noheader

   Input tables have no header row, cannot use --measure
   and --micro options then.

.. option:: --noid

   Input tables have no label/subject ID column at index
   0.

.. option:: --output OUTPUT, -output OUTPUT

   Name of output text file.
