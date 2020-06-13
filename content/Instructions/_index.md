---
title: "Instructions"
date: 2020-06-12T02:53:34-05:00
pre : "<i class='fa fa-check-circle'></i> "
draft: false
chapter : false
weight : 1
---

This set of tutorials are written in [Python](https://www.python.org/)
and they act as *stand-alone* notebooks. There are 2 ways of accessing them.

### Using Google's Colab

The ideal method of accessing these notebooks and resources is through
[My Binder](https://mybinder.org/) or 
[Google Colab](https://colab.research.google.com/).

You can simply click on the *badge* for opening it on **MyBinder** or
**Google Colab**:

[![Binder](https://mybinder.org/badge_logo.svg)]({{%siteparam "mybinder_repo_url"%}})

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]({{%siteparam "google_colab_repo_url"%}})

Just press on it and it will redirect you to the website dedicated to hosting
these notebooks.

### Getting the repository onto your computer

The first method of accessing the set of notebooks and resources is by
*cloning* the whole repository into your computer. In that way, you will
be able to :

- Install the necessary Python packages
- Run each notebook on its own and check the results yourself.

For this to work, you will first need to:

1. ***Clone your repository to specified directory***

    - Go to your `Documents` directory (or any other directory)

        ```bash
        # Let's go to your Documents folder
        cd $HOME/Documents
        ```

    - Clone the directory : Keep in mind that you **don't** have to clone it
      into `Documents`, but you can choose *any* other directory.

        ```bash
        git clone https://github.com/vcalderon2009/2020_06_CA_Astro_Data_Science_Workshop.git
        ```

    - Go into the directory

        ```bash
        cd ./2020_06_CA_Astro_Data_Science_Workshop
        ```

    - Checkout the `master` branch

        ```bash
        git checkout master
        ```

2. **Create a new Python environment**
    
    - The next step is to create a new Python environment for the project

        ```bash
        make create_environment
        ```

        This will create the necessary Python environment for the project.
        If you have [Anaconda](https://www.anaconda.com/) installed on your
        computer, this command will create a new Python environment with
        the name `2020_06_CA_Astro_Data_Science_Workshop`.

    - If using *Anaconda*, you will have to activate the environment:

        ```bash
        conda activate 2020_06_CA_Astro_Data_Science_Workshop
        ```

        or if you're using [venv](https://docs.python.org/3/library/venv.html),
        you can activate it as:

        ```bash
        workon 2020_06_CA_Astro_Data_Science_Workshop
        ```

        assuming you have it properly installed.

    - Install the necessary packages

        Now that the Python environment exists, you will need to
        **install the packages** into the environment:

        ```bash
        make requirements
        ```

3. **Accessing the notebooks**

    - You can finally access the notebooks of the project by:

        ```bash
        # Going into the `notebooks` directory
        cd notebooks

        # Start jupyter lab
        jupyter lab
        ```

> You can now look through the different notebooks and play around with them!
