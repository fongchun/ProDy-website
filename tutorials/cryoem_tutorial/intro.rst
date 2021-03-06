Introduction
===============================================================================

This tutorial shows how to use cryo-em electron density data to perform 
elastic network model analysis. The electron density maps could be gathered 
from the electron density map database EMDDatabank. 


Required Programs
-------------------------------------------------------------------------------

Latest version of ProDy_ is required.

Recommended Programs
-------------------------------------------------------------------------------

We recommend a visualization program too, such as VMD_.

Getting Started
-------------------------------------------------------------------------------

To follow this tutorial, you will need the following files:

.. files.txt will be automatically generated

.. literalinclude:: files.txt


We recommend that you will follow this tutorial by typing commands in an
IPython session, e.g.::

  $ ipython

or with pylab environment::

  $ ipython --pylab


First, we will make necessary imports from ProDy and Matplotlib
packages.

.. ipython:: python

   from prody import *
   from pylab import *
   ion()

We have included these imports in every part of the tutorial, so that
code copied from the online pages is complete. You do not need to repeat
imports in the same Python session.

.. _EMDDatabank: http://www.emdatabank.org
