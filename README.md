PyBossa application for Project Noah missions
=============================================

You can export a Project Noah mission using their CSV exporter link, copy the
link and import it directly in your PyBossa server thanks to the CSV importer
(use the CSV option).

Then, all you have to do is to use the template.html as a template for your
mission.

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

Please, check the full documentation here:

http://docs.pybossa.com/en/latest/user/create-application-tutorial.html
