.. include:: /Includes.rst.txt
.. _columns-number-properties-size:

====
size
====

.. confval:: size ('type' => 'number')

   :Path: $GLOBALS['TCA'][$table]['columns'][$field]['config']
   :type: integer
   :Scope: Display

   Abstract value for the width of the :code:`<input>` field. To set the number
   field to the full width of the form area, use the value 50. Minimum is 10.
   Default is 30.
