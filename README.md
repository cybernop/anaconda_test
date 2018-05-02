# annaconda_test

## Install

### MacOS
1. Download the installer:
    * [Miniconda installer for macOS.](https://conda.io/miniconda.html)
    * [Anaconda installer for macOS.](https://www.anaconda.com/download/)
2. Install:
    * Miniconda—In your Terminal window, run:
         ```
        bash Miniconda3-latest-MacOSX-x86_64.sh
         ```   
    * Anaconda—Double-click the ``.pkg`` file.

3. Follow the prompts on the installer screens.
If you are unsure about any setting, accept the defaults. You can change them later.
4. To make the changes take effect, close and then re-open your Terminal window.
5. [Test your installation.](https://conda.io/docs/user-guide/install/test-installation.html)

## Create new Environment
Create a new environment named ``test`` with Python 3.6 and ``<package>``

    conda env create -n test python=3.6 <package>
    
### From environment.yml file
Create an environment from existing definition

    conda env create -f environment.yml

## Exporting Environment to yml file
Export the currently active environment and writing it to ``environment.yml``:
   
    conda env export > environment.yml
   
## Remove Environment
Remove the environment with the name ``test``

    conda remove -n test --all
