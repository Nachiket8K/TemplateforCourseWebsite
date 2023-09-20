# Minimalist Installation

## A Minimalist Approach: Conda (Recommended for Long-term Learning)

If you want a more minimalist installation that only includes the barebones (that can be extended) of what's needed in this context, and/or you are not running Windows 10 Pro, macOS, or Linux, the recommended approach is to do a conda installation. This route will install a Python distribution natively with the libraries we will need. Note that no interactive extensions or R packages are installed in this case. Also, be aware that the installation is less stable as it relies on the specific versions for your OS and latest releases.

### How to Install

1. **Install Miniconda:** Download the Miniconda installer appropriate for your OS from the [official link](https://docs.conda.io/en/latest/miniconda.html). Choose the Python 3.x (e.g., 3.9) version, not Python 2.
    - Head over to the [Download Page](https://docs.conda.io/en/latest/miniconda.html) and select Python 3.9.
    - Click on the relevant file in the Python 3.9 section (highlighted in red).

2. **Locate Installer:** This will download the Miniconda installation file. Choose where to place it (e.g., the Desktop folder) or it will default to a location (like the Downloads folder).

Once you have miniconda installed, we need to set up an independent virtual environment that isolates all the functionality we need.

But first, *what are environments* and *do you need them?*

### Setting Up a Virtual Environment

#### What are Environments?

Environments in Python are like sandboxes with different versions of Python and/or packages. You can create, export, list, remove, and update environments. To switch between environments, you *activate* or *deactivate* them.

For this course, we want to have a bit more control on the packages that will be installed with the environment so we will create an environment with a so-called YAML file called 'install_gds_stack.yml'.

To learn more about virtual environments, you can also go [here](https://cusp.tbm.tudelft.nl/courses/epa1316/software/environment/).

#### Creating an Environment

1. **Open a Terminal:** Depending on your OS:
    - **Windows**: "Anaconda Command Prompt"
    - **macOS**: "Applications -> Utilities -> Terminal"
    - **Linux**: "ctrl+alt+T"

2. **Get YAML File:** Download `install_gds_stack.yml` from [here](https://cusp.tbm.tudelft.nl/courses/epa1316/resources/install_gds_stack.zip) and unzip it.
  
3. **Navigate to Folder:** Use the command `cd /path/to/Downloads`.

4. **Create Environment:** Run `conda env create -f install_gds_stack.yml`.

#### TIP

Depending on the speed of your connection, this step will take a while (but no less than 15-20 minutes). Grab a cuppa and be patient!

This has created the gds environment, congratulations! We are almost there. Now we need to activate the environment.

### Activating the Environment

1. Run `conda activate gds`. You'll see the environment name in the command prompt.


You should see the name of the environment at the start of your command prompt in parenthesis.

Verify that the new environment was installed correctly:

2. **Verify Installation:** Run `conda list`.

For further management, consult [Manage conda environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

### Using Environment in Jupyter Lab

1. **Install Kernel:** `ipython kernel install --name "gds" --user`

2. **Open Jupyter Lab:** With the environment active, open a Jupyter Lab instance with `jupyter lab`.

