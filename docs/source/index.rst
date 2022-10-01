:github_url: https://github.com/pytorch/multipy

torch::deploy [Beta]
=====================

torch::deploy is a system that allows you to create multiple python interpreters which execute PyTorch models, and run them in a single C++ process. Effectively, it allows people to multithread their pytorch models.
For more information on how torch::deploy works please see the related `arXiv paper <https://arxiv.org/pdf/2104.00254.pdf>`_.


Documentation
---------------

.. toctree::
   :maxdepth: 1
   :caption: Usage

   setup.md
   quickstart.md
