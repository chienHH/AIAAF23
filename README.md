=============
AIAAF 2023 Workshop Unity and RL in Architecture


**News:**

    01-05-2023: This package contains materials for the  `Unity and RL Workshop AIAAF 2023<https://aiaaf2023-unityai-workshop.splashthat.com/>`_
    for the AI-aided Architectural Farbication Symposium 2023.

Installation
------------

.. Write installation instructions here

**Prerequisites**

0. Operating System:
    **Windows 10/11** and **Mac(!)**
1. _`Unity3D2022.2.17f1<https://unity.com/download>`_
    We will use Unity mainly to run all the simulation and reinforcement learning. The reinforcement learning part is achieved by `MLAgents <https://github.com/Unity-Technologies/ml-agents>`_
    The robotic articulation is achieved by `Unity Robotics Hub <https://github.com/Unity-Technologies/Unity-Robotics-Hub>`
1. `Rhinoceros 3D 7.0 <https://www.rhino3d.com/>`_
    We will use Rhino / Grasshopper as a frontend for inputting
    geometric and numeric paramters, and structural analysis. The integration between Grasshopper and Unity
    environments is made possible by `Karamba3D <https://karamba3d.com/>`_
    and `Junichiro Horikawa <https://github.com/jhorikawa/MeshStreamingGrasshopper>`_.
2. `Git <https://git-scm.com/>`_
    We need ``Git`` for fetching required packages from github.
3. `Anaconda <https://docs.conda.io/en/latest/miniconda.html>`_
    We will install all the required python packages using
    'Anaconda'. Anaconda uses
    **environments** to create isolated spaces for projects'
    depedencies. Alternatively, you can use Miniconda.
4. Karamba3D for Unity (Please install from here). Note this is only for Windows OS.
5. Make sure you have Microsoft .NET Framework 4.5 installed. (This should be by default for Windows 11)
6. `Microsoft Visual Studio Build tools <https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16>`_
    Our simulation environment ``pybullet`` has a C++ backend, which needs
    ``Microsoft Visual C++ 14.0`` to compile and build the python bindings. Note that this is needed only for Windows OS.

**Working in a conda environment**

It is recommended to set up a conda environment to create a clean, isolated space for
installing all the required python packages for MLAgents. We've provided a conda environment file
to make this process easy - please do the following steps:


Congrats! 🎉 You are all set!

Troubleshooting
---------------

Sometimes things don't go as expected. Checkout the `troubleshooting <./docs/troubleshooting.rst>`_ documentation for answers to the most common issues you might bump into.

Credits
-------

This package was created by Chien-hua Huang <chien-hua.huang@Arup.com> `@chienH_H <https://github.com/chienH_H>`_
with `collaborators <./AUTHORS.rst>`_.
