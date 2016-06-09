# A Whirlwind Tour of the Jupyter Notebook Ecosystem

The following files form the basis for an interactive presentation of the Jupyter Notebook, it's features as a rich HTML document, Python interaction, and some neat little tricks. Please note that quite a few of them are adaptations of example notebooks.

1. The Notebook, in its simplest use-case, can be an IPython shell replacement with multi-line editing ([Notebook](shell_replacement.ipynb)).
2. Markdown formatting allows for some pretty annotation and [literate programming](https://en.wikipedia.org/wiki/Literate_programming) ([Notebook](markdown_formatting.ipynb)).
3. Modern browsers allow for some rich display of objects allowing for some neat representations ([Notebook](rich_output.ipynb)).
4. Line and cell magics are basically functions that behave like keyword-functions. They are pretty useful! ([Notebook](magics.ipynb)).
5. The notebook allows for the inclusion of plots making it a fantastic tool for generating data analysis reports ([Notebook](plots.ipynb)).
6. Interactive widgets increase the usefulness of the notebook as a reporting tool since data can be investigated more thoroughly without editing code ([Notebook](interact.ipynb)).

I realized that for the interactive widgets I needed to issue the following
command in a terminal. Please enjoy playing with sliders ;)

    jupyter nbextension enable --py widgetsnbextension

# Resources

## General

* Of course, [the main website](http://jupyter.org/) has a wealth of information. Links on how to [interact with the community](http://jupyter.org/community.html) and much more.
* [Documentation](http://jupyter.readthedocs.io/en/latest/index.html) - hated by some and a little confusing at times due to the switch from IPython Notebook to Jupyter with a Python kernel but always an indispensable tool.
* Quickly [try out the notebook](https://try.jupyter.org/).

## Working with the Notebook

* [The examples](https://github.com/jupyter/notebook/tree/master/docs/source/examples/Notebook) that come with the Jupyter Notebook package itself.
* You can share notebooks via Gists or repositories on Github and look at them using [nbviewer](http://nbviewer.jupyter.org/).
* [A gallery](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#introductory-tutorials) of notebooks with really broad topic areas.
* [Javascript extensions](https://github.com/ipython-contrib/IPython-notebook-extensions/wiki/Home-4.x-%28Jupyter%29) that can make your life easier (or more interesting).

## Multi-user Setting

* The [JupyterHub](https://jupyterhub.readthedocs.io/en/latest/).
* [Grading tools](https://github.com/jupyter/nbgrader) for the classroom.

# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Unless where adapted from others, this work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
