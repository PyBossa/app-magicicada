PyBossa application for Project Noah missions
=============================================

You can export a Project Noah mission using their CSV exporter link, copy the
link and import it directly in your PyBossa server thanks to the CSV importer
(use the CSV option).

Then, all you have to do is to use the template.html as a template for your
mission.

![alt screenshot](http://i.imgur.com/BdAUSfw.png)

Testing the application
=======================

You need to install the pybossa-client first (use a virtualenv):

```bash
    $ pip install pybossa-client
```
Then, you can follow the next steps:

*  Create an account in PyBossa
*  Copy under your account profile your API-KEY
*  Run python createTasks.py -u http://crowdcrafting.org -k API-KEY -t
*  Open with your browser the Applications section and choose the Magicicada app. This will open the presenter for this demo application.

Documentation
=============

We recommend that you read the section: [Build with PyBossa](http://docs.pybossa.com/en/latest/build_with_pybossa.html) and follow the [step by step tutorial](http://docs.pybossa.com/en/latest/user/tutorial.html).

**NOTE**: This application uses the [pybossa-client](https://pypi.python.org/pypi/pybossa-client) in order to simplify the development of the application and its usage. Check the [documentation](http://pythonhosted.org/pybossa-client/).


LICENSE
=======

Please, see the COPYING file.


Acknowledgments
===============
The thumbnail has been created using a [photo](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC1963320/) from Kathryn M. Fontaine, John R. Cooley, and Chris Simon from the paper: [Evidence for Paternal Leakage in Hybrid Periodical Cicadas (Hemiptera: Magicicada spp.)](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC1963320/) (license Creative Commons Attribution License). 
