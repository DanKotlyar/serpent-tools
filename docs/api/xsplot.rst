.. _xsplot:

================
XSPlot Reader
================

The :py:class:`~serpentTools.parsers.xsplot.XSPlotReader`
is designed to read the files generated by the 
`set xsplot output <http://serpent.vtt.fi/mediawiki/index.php/Input_syntax_manual#set_xsplot>`_.
Output appears as a Octave or Matlab style file matching the original Serpent input name,
but with "_xs<bustep>.m" appended, where <bustep> is an integer representing the corresponding
depletion step.

The reader stores cross section data alongside convenient tabulation plotting and tabulation
methods in  :py:class:`~serpentTools.objects.xsdata.XSData` objects.

.. autoclass:: serpentTools.parsers.xsplot.XSPlotReader

