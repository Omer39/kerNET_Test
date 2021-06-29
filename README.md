# kerNET_Test
In this repository, I am documenting the steps that I followed to test https://github.com/michaelshiyu/kerNET

In order to run the modular model, These steps were followed. 

1- Clone the GitHub repository to Google Colab.

   a-)  Open a folder (project_folder) in Drive/ColabNotebooks and a python notebook (mainCode.ipynb) in this folder.

   b-)  Mount Google drive 
              from google.colab import drive
              drive.mount('/content/gdrive/')
              %cd /content/gdrive/My\ Drive/ColabNotebooks/project_folder
   
   c-)  Clone the repository. ! git clone https://github.com/michaelshiyu/kerNET.git

2-  In order to run modular_train.py & test.py these files were moved into the kerNET folder. 
3-  mainCode.ipynb and kerjNET folder are kept in the main folder named as “project_folder”.


Takeaways: 
How to connect a GitHub repository to Google Colab (Look at the first step)
How to run .py files in Colab >>> ! python demofile.py  (Adjust the current directory)

Problem:
Here, the .py files can call functions only when the functions are in a subfolder. (Look at the 2nd step.) 

