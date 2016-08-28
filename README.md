cookiecutter_omscs
==================

A cookiecutter template for GaTech OMSCS course work.

After 5 semesters of OMSCS, I've settled into a nice rhythm with my course work.
This project is designed to streamline my workflow and make it easy to get
started with a new class.

My workflow is centered around [Jupyter](http://jupyter.org/) and LaTeX.  I
primarily use python, but am excited to try out the [C Kernel for Jupyter](https://github.com/brendan-rius/jupyter-c-kernel) in the [High Performance Computing](http://cse6220.gatech.edu/fa16-oms/) course this semester.

**Remember, it may be against the GaTech Academic Honesty policy to make your
repo public while you are in a course**

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
* Generate a new Cookiecutter template layout: `cookiecutter gh:jlmcgehee21/cookiecutter_omscs`

* Install Jupyter 
  * `$ cd my_new_course`
  * `$ pip install -r requirements.txt`

Features
--------
* `Makefile` to simplify tasks. Comes baked in with:
  * `make new_project`: create `new_project` directory that has the same
    structure as `./projects/project1`

* Convenient directory structure so you have one less thing to think about:
```
.
├── Makefile
├── README.md
├── exercises <- "Short" coding exercises/assignments
│   └── algorithm.py
├── notes <- Jupyter notebooks for lecture notes
│   ├── img <- A place to put images referenced in your notes
│   └── lesson1.ipynb
├── projects <- Big projects
│   └── project1
│       ├── README.md
│       ├── code
│       ├── paper
│       └── references
└── requirements.txt <- Put your python requirements here.
```

License
-------
This project is licensed under the terms of the [MIT License](/LICENSE)
