:orphan:

.. ibioic_install_blast:

====================
Installing ``BLAST``
====================

We use the sequence search tool `BLAST`_ at several points in the course. This can be
installed as follows:

------------------------
Linux/macOS installation
------------------------

`BLAST`_ is available through `Bioconda`_

.. code-block:: bash

    conda install blast

--------------------
Windows installation
--------------------

1. Download ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/2.7.1/ncbi-blast-2.7.1+-win64.exe with your web browser.
   If that FTP links does not work, try HTTP instead http://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/2.7.1/ncbi-blast-2.7.1+-win64.exe
2. Run this installer using the defaults, it should put BLAST under ``C:\Program Files\NCBI\blast-2.7.1+``
3. Test one of the BLAST programs can be run by executing the command ``blastn -h`` in the Git Bash terminal.

.. _Bioconda: https://bioconda.github.io/
.. _BLAST: ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/
