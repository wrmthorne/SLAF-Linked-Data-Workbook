# SLAF-Linked-Data-Workbook

This workbook contains a simple project for identifying salient entities in a cultural heritage text and disambiguation them using [Getty ULAN](https://www.getty.edu/research/tools/vocabularies/ulan/). The notebook will cover the tagging of entities, writing very simple SPARQL queries to match people's names against records in ULAN and then wrapping the names with basic markup.

The workbook does not require you to write any python but there are optional exercises for extending the provided SPARQL queries if you want to have a go.


## Running with Google Colab

Here are the instructions to open and run the notebook in your browser using colab. This requires an internet connection to run as it is hosted on a cloud server but it means you can run the notebook without having to worry about your PC specs:

1. Open Google Colab at the following link: https://colab.research.google.com/
2. In the top left, select `File` and then `Open Notebook`
3. In the left menu of the opened window, select `GitHub`
4. In the search bar at the top of that window, enter the URL to this notebook and press enter: https://github.com/wrmthorne/SLAF-Linked-Data-Workbook/blob/main/workbook.ipynb

If you have not signed in with a Google account, you will be prompted to do so before you can run any cells.

## Using the notebook

A Python Notebook allows you to have short snippets of code that can be run independently of the rest of your script, alongside markdown to help explain the content. The notebook has been setup to fetch and install any additional libraries and data for you so you don't need to worry about setting up the project.

Individual code cells can be run by clicking the `Play` (Circle with a right pointing triangle) button on the left of each code cell or by clicking in the cell and using the keyboard shortcut `CTRL` + `ENTER`. Cells may depend on code run in previous cells so make sure to run each code cell as you go to avoid unexpected behaviour.

`WARNING`: If you run code in a cell which sets a variable `a`, that value of `a` is set across the whole notebook, even in cells above it.