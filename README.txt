Required steps for running the python script
--------------------------------------------
NOTE 1: Only step 1 is needed to run the script by default. So, if the datasets are present in the same folder as the script file, the script will run successfully. STEP 2 is needed ONLY for visualizing the Decision trees. This code is commented in the script by default.
If the visualization of the decision treeis to be seen, please perform STEP 2 and uncomment required code in the script. (The code that needs to be uncommented can be found by searching "uncomment" in the script.

1. Datasets should be present in same folder where the python script is located. They are:
	a) energydata_complete.csv - Energy dataset
	b) trial.csv - Audit dataset
2. Installation of "Graphviz 2.38". The steps are given below: (This is needed for visualizing the decision trees)
	a) Download Graphviz from http://www.graphviz.org/download/ (for windows or mac).
	b) Run "graphviz-2.38.msi" and install it.
	b) After installation, add "C:\Program Files (x86)\Graphviz2.38\bin" to PATH Environment variable.
3. Restart Jupyter/Spyder