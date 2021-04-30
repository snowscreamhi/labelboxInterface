# Labelbox Interface

Exposed link to index.html:
http://labelbox-interface.snowscreamhi.vercel.app/

### Note:
You must update the Vercel project to reflect GitHub changes.
https://vercel.com/snowscreamhi/labelbox-interface


# Qualitative Analysis: Custom Labelbox Interface and Labelbox Data Generation

This repository contains an exposed HTML and CSS file that Labelbox uses to show a custom interface to researchers. Labelbox has good resources for instructions on how to create a custom interface. Specifically, these links will be useful:

- https://docs.labelbox.com/custom-interface/en/index-en#step-2--install-your-custom-editor-in-labelbox
- https://github.com/Labelbox/Labelbox/tree/master/custom-interfaces
- https://www.loom.com/share/97e20c8e3ab345ad996cc4c8f3b4cdae

This repository also contains a Python Notebook that describes how to generate data compatible with this interface, as well as how to code other useful functions for Labelbox. This Python Notebook is meant to be run in Google Colab, but could probably easily be adapted to run on a local machine. NOTE: The data referenced in this code is not available in this repository, but is available here: https://www.kaggle.com/snap/amazon-fine-food-reviews

If you wish to copy this code or create a similar custom interface, I suggest cloning this code and following the tutorials linked above and the tutorials linked in the Python Notebook.

## General Notes for HTML interface:
- The index.html was mostly copied from Labelbox's example custom interfaces (see the second link above). We made certain modifications with it to make it functional for our custom interface, but the code is not very clean.
- A better understanding of HTML and CSS could help to develop a more useful pipeline for modifying/improving the custom interface.
- The index.html occasionally uses the styles.css file to modify the look of the page. For best practice, the styles.css should be used at all times (i.e. the hard-coded styles within index.html should be removed and replaced with css styles).
