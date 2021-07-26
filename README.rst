Deploy Dask on Job Queueing systems
===================================

|Build Status| |Doc Status| |Gitter| |Version Status|

This fork of Dask-jobqueue was modified to be used with a HPC system where the dask-workers are run in singularity container where the qsub commands are exectued through SSH due to HPC restrictions.

LICENSE
-------

New BSD. See `License File <https://github.com/dask/dask-jobqueue/blob/main/LICENSE.txt>`__.

.. _documentation: https://jobqueue.dask.org/en/latest/
.. |Build Status| image:: https://github.com/dask/dask-jobqueue/workflows/CI/badge.svg
   :target: https://github.com/dask/dask-jobqueue/actions
.. |Doc Status| image:: https://readthedocs.org/projects/dask-jobqueue/badge/?version=latest
   :target: https://jobqueue.dask.org/en/latest/
   :alt: Documentation Status
.. |Gitter| image:: https://badges.gitter.im/Join%20Chat.svg
   :alt: Join the chat at https://gitter.im/dask/dask
   :target: https://gitter.im/dask/dask?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
.. |Version Status| image:: https://img.shields.io/pypi/v/dask-jobqueue.svg
   :target: https://pypi.python.org/pypi/dask-jobqueue/
