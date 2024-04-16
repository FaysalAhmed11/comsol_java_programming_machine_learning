# comsol_java_programming_machine_learning

For python:
step 1- upload the dataset in the google drive.
step 2-mount the google drive with a co-lab file.
step 3-make sure to add the path correctly for the specific dataset.
step 4-run the algorithm and get the result.

For Java:
step 1-create a java project in eclipse.
step 2-while creating the project, add the external libraries from COMSOL plugins folder . For my machine the path is: "C:\Program Files\COMSOL\COMSOL62\Multiphysics\plugins"
step 3-copy the java code that was saved from COMSOL to the eclipse.
step 4-now in eclipse under the Run tab, there is an option Run configuration->Java Application->(your file.java)->Environment->Add.
step 5-while press Add,a new window will pop up, there put Name=PATH and Value="C:\Program Files\COMSOL\COMSOL62\Multiphysics\lib\win64" this path and then apply it.
step 6-now in the java main function, add this line at the beginning :  ModelUtil.initStandalone(false);  put this line at the end of the main function: System.exit(0).
step 7-modify the code as you want and run the code, get the result (data).
