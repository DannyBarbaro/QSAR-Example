# QSAR-Example
A simple Jupiter notebook that walks through a basic QSAR for a small chemical sdf file

# Dependencies
This example has a good amount of dependencies to run. The first major dependency is the anaconda python distribution.

Instructions will by provided for using a MacOS computer

> brew install anaconda
> source <path to conda>/bin/activate
> conda init
> conda install rdkit
> pip3 install jupyter
> pip3 install numpy
> pip3 install sklearn

# How to Run
Running is simple. After the dependencies are in places, open the jupter notebook how you please and run the cells sequentially

# How to Export 
The notebook can be exported to html for easier viewing with the command line arguement:
> jupyter nbconvert qsar-example.ipynb --to html --output (output_name).html
