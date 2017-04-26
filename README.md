dalliance-notebook
===============================

A Jupyter widget for displaying genomic data using the Dalliance browser

Installation
------------

To install use pip:

    $ pip install dalliance-notebook
    $ jupyter nbextension enable --py --sys-prefix dalliance-notebook


For a development installation (requires npm),

    $ git clone https://github.com/sbliven/dalliance-notebook.git
    $ cd dalliance-notebook
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix dalliance-notebook
    $ jupyter nbextension enable --py --sys-prefix dalliance-notebook
