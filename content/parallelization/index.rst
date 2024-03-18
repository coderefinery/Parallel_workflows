Embarassingly Parallel Problems
===============================

.. warning::

   This is under construction.  The schedule is not final, please see
   the planning HackMD (not linked here, check on CodeRefinery chat)
   for the current planning. 

.. admonition:: Course instance in April 2024

   You can follow the dates this course is given on the `course page
   <https://scicomp.aalto.fi/training/scip/workflows-2023/>`__.
   Dates are not yet known and registration is not yet open, though.

In this lesson we will introduce the concept of embarassingly parallel 
code, and how we can use this property to easily distribute heavy 
computation to multiple processes without the necessity of falling back
on mechanisms within the language. 

.. prereq::

   * Basic HPC usage course (if you don't have, many of the things we
     talk about won't make sense, but you might pick up something
     anyway).
   * A bit of experience using a HPC cluster (technically optional,
     but will allow you to engage with the material at a deeper
     level).
   * Access to some HPC computer cluster to do most exercises.
     (Slurm-based, but most are these days).  (If you don't have, you
     can't do all exercises - but still might learn something!)


.. csv-table::
   :widths: auto
   :delim: ;

   10 min ; :doc:`motivation`
   10 min ; :doc:`concepts`
   10 min ; :doc:`code_adaptions`
   20 min ; :doc:`array_jobs`
   20 min ; :doc:`submission_by_script`
   5 min ; :doc:`conclusions`


.. toctree::
   :maxdepth: 1
   :caption: The lesson

   motivation
   concepts
   code_adaptions
   array_jobs
   submission_by_script
   conclusions

