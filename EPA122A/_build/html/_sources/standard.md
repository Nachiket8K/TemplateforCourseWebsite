# Standard Installation

## A Standard Approach: Anaconda Installer (Easiest to Work With)

Follow the instructions on the [Anaconda website](https://www.anaconda.com/) and install a distribution which contains Python 3.9. Once the software is installed, double click on it, and confirm that you have something called JupyterLab already installed within it. You are done!

## Setting Up a Virtual Environment

### What are Environments?

Environments in Python are like sandboxes that have different versions of Python and/or packages installed in them. You can create, export, list, remove, and update environments. Switching or moving between environments is called *activating* the environment. When you are done with an environment, you may *deactivate* it.

For this course, we want to have a bit more control on the packages that will be installed with the environment so we will create an environment with a so-called YAML file called `[install_gds_stack.yml](https://cusp.tbm.tudelft.nl/courses/epa1316/resources/install_gds_stack.zip)`.

To learn more about virtual environments, you can also [go here](https://cusp.tbm.tudelft.nl/courses/epa1316/software/environment/).

### Creating an Environment From an `environment.yml` File

1. Get the installer file from [here](https://cusp.tbm.tudelft.nl/courses/epa1316/resources/install_gds_stack.zip) and unzip it.
2. Open up the Anaconda Navigator:
    - Go to "Environments"
    - Click on "Import"
    - From your local drive, import the installer file you just downloaded
    - Give the environment a name, like "gds"
    - Remember to keep the option "Overwrite existing environment" unchecked

### TIP:
Depending on the speed of your connection, this step will take a while (but no less than 15-30 minutes). Grab a cuppa and be patient!

This has created the `gds` environment, congratulations! We are almost there. Now we need to *activate* the environment. For this, just select the right environment and open a Jupyter Lab notebook.
