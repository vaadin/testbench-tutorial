Vaadin TestBench Tutorial
=========================

This is the final code produced by the [Vaadin TestBench Tutorial](https://vaadin.com/docs/v8/testbench/testbench-tutorial.html).


Running the example
-------------------
The following command starts a jetty server and runs the tests in Firefox:
<pre>mvn verify</pre>


Importing in Eclipse
--------------------
Make sure you have "Eclipse IDE for Java EE Developers" and Maven integration "m2e-wtp" installed. You will get Eclipse from http://eclipse.org/downloads/ and plugins through Help -> Eclipse Marketplace... menu

To checkout and run the project from Eclipse, do:
- File -> Import...
- Check out Maven Projects from CMS
- Choose Git from SCM menu and set URL to git://github.com/vaadin-samples/testbench-tutorial.git
  - If you do not see "Git" in the SCM menu, click "Find more SCM connectors in the m2e Marketplace" and install "m2e-egit"
- Now you should have an "testbench-tutorial" project in your workspace
- To run it, right click and choose Run As -> Run on Server
- Start experimenting

Note that if you are missing EGit plugin, "Maven SCM Handler for EGit" or a local server to run the project on, you will be asked to install these while doing the above.
