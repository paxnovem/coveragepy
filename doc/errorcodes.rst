Error Code Groupings
-----------

.. list-table:: Error Code Groupings
   :widths: 25 25 50
   :header-rows: 1

   * - Error Id
     - Error description
   * - COV0XX
     - Configuration Error
   * - COV1XX
     - Report Generation
   * - COV2XX
     - Plugin Errors
   * - COV3XX
     - Data Errors
   * - COV4XX
     - Reserved
   * - COV5XX
     - Runtime Errors
   * - COV6XX
     - Reserved
   * - COV7XX
     - Reserved
   * - COV8XX
     - Reserved
   * - COV9XX
     - Misc Errors


.. _COV300:
E: COV300
=========

``coverage.exceptions.DataError: Couldn't use data file``

This error is potentially caused by one of the following causes:
- The file was deleted by an external process
- Multiple instances of coverage are running in parallel using the same data_file name 
