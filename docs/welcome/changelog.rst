.. _changelog:

*********
Changelog
*********

.. _v0.3.1:

:release-tag:`0.3.1`
====================

* :pull:`118` - Support for ``SERPENT`` 2.1.30
* :bug:`119` - SampledDepletedMaterial now respects the value of `xUnits` 
  - :squashed:`120`
* :pull:`114` - Standalone branches in the coefficient files are stored
  and accessed using a single string, rather than a single-entry tuple
  ``branches['myBranch']`` vs. ``branches[('myBranch', )]``

    
.. _v0.3.0:

:release-tag:`0.3.0`
====================

* :pull:`109` - Capability to read history files
* :pull:`107` - DepletionReader can now plot data for some or all materials

.. _v0.2.2:

:release-tag:`0.2.2`
====================

* :pull:`82` - Command line interface and some sub-commands
* :pull:`88` - Pre- and post-check methods for readers
* :pull:`93` - Detector and Depletion Samplers
* :pull:`96` - Better mesh plotting for detector
* :bug:`99` - Negative universe burnup with branching reader - :squashed:`100`
* :py:attr:`serpentTools.objects.containers.Detector.indexes` are now zero-indexed
* The PDF manual is no longer tracked in this repository

