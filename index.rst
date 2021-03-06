.. CESM Porting Documentation documentation master file, created by
   sphinx-quickstart on Fri Oct 30 17:26:59 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

##########################
Aether Model Documentation
##########################

Welcome to the documentation of the Aether Model.

Aether is an extremely flexible community-based multi-scale
ionosphere-thermosphere model. Ensemble capability, data assimilation, and
uncertainty quantification are fundamentally integrated into the core of the
model.

Aether is an open-source model, allowing contributors from across the globe to
create, incorporate, and commit new solvers, schemes, and physics modules.

Users have straightforward defaults in the model configuration, but are able to
select any contributor's modules in order to allow for maximum flexibility.
For example, users can employ faster, less accurate solvers (for prediction)
and slower, more accurate solvers (for science).



.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Getting Started
   
   /download/github
   /download/system-requirements

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Data Assimilation

   data-assimilation/dart
   data-assimilation/filtering-theory

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Uncertainty Quantification

   uncertainty-quantification/monte-carlo

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Verification

   verification/verification-tests

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Education

   /education/coding-school

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Contributing

   /contributing/contributors-guide
   /contributing/core-team
   /contributing/rst-style-guide
   /contributing/submodules

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Releases

   releases/armadillo
   releases/bandicoot
   releases/cassowary
