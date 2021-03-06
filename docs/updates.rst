
.. Change log


.. _updates:

Change log
==========

    * 04/2017: Release_ of version 0.1.3
        - Initial stable version released.

    * 07/2017: Release_ of version 0.1.4
        - Prediction array dtype option (default=float32)
        - :ref:`Feature propagation <propa-tutorial>`
        - :ref:`Clustered subsemble partitioning <subsemble-tutorial>`
        - No memmaps passed to estimators (only ndarray views)
        - Global configuration (mlens.config)
        - Scoring exception handling

    * 07/2017: Release_ of version 0.1.5
        - Possible to set environmental variables
        - ``spawn`` as default start method for parallel jobs (w. multiprocessing)
        - Possible to specify ``y`` as partition input in :ref:`Clustered subsemble partitioning <subsemble-tutorial>`
        - Minor bug fixes
        - Refactored backend for streamlined front-end feature development

.. _Release: https://github.com/flennerhag/mlens/releases
.. _Feature propagation: