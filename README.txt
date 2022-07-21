Programming Language Required:
Python v3.8 (or above)

Libraries Required:
1) numpy 
2) pandas
3) re
4) os
5) pickle
6) time 
7) sklearn

Note for libraries:
1. Please install sklearn in your local system before proceeding with the steps. 
We have installed the libraries in a Linux system (Ubuntu 20.04 LTS). Make sure you have installed
them as per your system (MacOS, Linux or Windows) as per their official documentation.

2. All the code files must run in the jupyter notebook.


Dataset Required:
1) NSL- KDD IDS dataset
2) NSA Snort IDS alert logs
3) DARPA IDS dataset
4) system generated dataset for Snort logs
Dataset is provided in the Dataset folder, for each of the following Dataset there is a seperate folder and output of preprocessing dataset are also sored in their respective Dataset folder of standard datasets.

Steps to run:

Step 1: Download the zip file uploaded and extract it in a folder.

Step 2: All the code files are in the main directory.

Step 3: Run "1 log_Read.ipynb". (It may take ~2mins depending on your processor).
        All the datafiles will be read and preprocessing will take place thereafter automatically the respective processed files will be created in the same folder.

Step 4: Run "2 parse_cpu_mem snort.ipynb". 
        It will monitor cpu utilization and memory consumption of your system when snort is running .

Step 5: Run "3 parse_cpu_mem suricata.ipynb". 
        It will monitor cpu utilization and memory consumption of your system when suricata is running .
        
Step 6: Run "4 plugin.ipynb". 
        It is intelligent plugin which uses ML to enchance snort or suricata detection of malicious attacks.

Step 6: Run "5 plugin-test.ipynb". 
        testing the features of plugin on testset.



Contact:
If you have any issues to run the project, please mail at any one of the following email ids.
{kajals21@iitk.ac.in}, {pranshus21@iitk.ac.in}, {utkarshs21@iitk.ac.in},{gsarkar21@iitk.ac.in},{gajenders21@iitk.ac.in}