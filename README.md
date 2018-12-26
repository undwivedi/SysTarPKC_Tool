# SysTarPKC_Tool

Note:

1. Full SysTarPKC_Tool.zip (about 33.722 MB) along with PaDEL_Descriptor software can be accessed from: https://drive.google.com/open?id=1IKPDpGyzDrerm3VLo0i5g9j8jFaLGJfE

2. To manage the limitations of file size of <25 MB, The SysTarPKC_Tool.zip without PaDEL_Descriptor software can also be access from GitHub.



Detailed protocol for usage of tool is as following:

Prepare 3D structure of query molecule, and save it as .sdf file.

Download Full SysTarPKC_Tool.zip (Since > 25 MB) from: https://drive.google.com/open?id=1IKPDpGyzDrerm3VLo0i5g9j8jFaLGJfE

Extract the .zip file and double click the executable ‘Run_SysTarPKC_Tool.jar’.

Click ‘Step1 button’, to open a file browser for selection of .sdf file of query molecule. This process will provide input value for SBML simulator, which is a value from PKC domain derived for query structure. This float value is input for SBMLsimulator.

Now click ‘Step2 button’, and load the ‘PKC_Model.xml’ model.

To configure SBMLsimulator, set two variables as cell = 1.0 ml and Q = “float value from Step 1”. Make sure that you have selected ‘Euler method for differential equation solver’ for End time = 100 and Number of steps = 1000. Now run the process.

After completion of process, go to ‘Computed Data’ tab, and pick the value for R1_0 variable at Time = 50.

Put the Collected R1_0 value into Text box before ‘Step 3 button’ and calculate value of ‘Selectivity Score’.

