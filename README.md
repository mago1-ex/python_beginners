How to open a jupyter notebook

Enter a Anaconda Powershell. In windows you can enter the Anaconda Powershell by searching for "anaconda".

Enter the directory where the notebooks lie by using 

cd "foldername" 

to change the directory. Use 

cd ..

to go one directory up.


In the folder you can open the jupyter notebook with

jupyter notebook





Using conda virtual environments for python projects can be created and managed.

A virtual environment is created by 

conda create -n "enironment_name" python="python_version"




A list of all conda environments is returned with the command

conda env list

an asterisk marks the active environment.


An environment is activated via

conda activate "enironment_name"



and deactivated via

conda deactivate

