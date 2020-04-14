.. Computational Software documentation master file, created by
   sphinx-quickstart on Tue Mar 31 12:45:28 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
.. figure:: img/CompSoft_banner.png

Welcome to the Introduction to Computer-based Physical Modeling Course!
========================================================================

The Python programming language is useful for all kinds of scientific and engineering tasks. You can use it to analyze and plot data. You can also use it to numerically solve scientific problems that are difficult or even impossible to solve analytically. Python is freely available and has been, due to its modular structure, extended with a nearly infinite number of different purpose modules.  

This course intends to introduce you into the programming with Python. It is aimed more to the beginner but we hope that more advanced users find it interesting as well.
We will start the course with and introduction to the Jupyter Notebook environment which we will be using throughout the course. Starting from there we will provide some introduction into Python and then show you some basic functionalities, like plotting and analyzing data by curve fitting, reading and writing of files which are some of the tasks you will encounter during your physics studies. We will also show you some more advanced topics of animating inside Jupyter and simulating physical processes in

* mechanics
* electrostatics
* waves
* quantum mechanics
* optics

At the end of the course we will also add some basic introduction into **machine learning** which is now becoming an important tool even in physics.

We will not present a comprehensive list of numerical simulation schemes, but use the examples to stimulate your curiosity. As there are slight differences in the syntax of different Python versions, we will in the following always refer to **Python 3** standards.


.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/lSIwZFeRpfQ" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

|
|


.. toctree::
   :maxdepth: 2
   :caption: Course Information:
   
   course-info/website.rst
   course-info/schedule.rst
   course-info/assignments.rst
   course-info/exam.rst
   course-info/resources.rst   
   course-info/instructor.rst
   
.. toctree::
   :maxdepth: 2
   :caption: Jupyter Notebooks:
   
   lectures/Intro/overview.rst
   notebooks/Intro/Introduction2Jupyter.ipynb
   notebooks/Intro/NotebookEditor.ipynb
   notebooks/Intro/EditCells.ipynb


.. toctree::
   :maxdepth: 2
   :caption: Lecture 1:

   lectures/L1/overview_1.rst
   notebooks/L1/1_variables.ipynb
   notebooks/L1/2_operators.ipynb
   notebooks/L1/3_datatypes.ipynb
   notebooks/L1/4_modules.ipynb
   lectures/L1/assignment_1.rst



.. toctree::
   :maxdepth: 2
   :caption: Lecture 2:

   lectures/L2/overview_2.rst
   notebooks/L2/1_numpy.ipynb   
   notebooks/L2/2_plotting.ipynb
   notebooks/L2/3_randomnumbers.ipynb
   lectures/L2/assignment_2.rst   
   
   
.. toctree::
   :maxdepth: 2
   :caption: Lecture 3:

   lectures/L3/overview_3.rst
   notebooks/L3/1_input_output.ipynb
   notebooks/L3/2_flowcontrol.ipynb   
   notebooks/L3/3_functions.ipynb  
   notebooks/L3/4_classes.ipynb  

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
