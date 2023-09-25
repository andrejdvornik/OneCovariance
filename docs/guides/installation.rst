Installation
============

The most recent stable version of ``OneCovariance`` should be installed directly from GitHub.

.. code-block:: bash

    git clone git@github.com:rreischke/OneCovariance.git
    cd OneCovariance
    conda env create -f conda_env.yaml
    conda activate cov20_env
    pip install .

If you do not want to use the conda environment, make sure that you have ``gfortran`` and ``gsl`` installed.
You can install both via ``conda``:

.. code-block:: bash

    conda install -c conda-forge gfortran
    conda install -c conda-forge gsl
    git clone git@github.com:rreischke/OneCovariance.git
    cd OneCovariance    
    pip install .

Once you have carried out these steps, you are ready to run the code.