# stat315final
This is the docker image used to store the final project for group 1 stat 315 spring 2024.\ 

first run the command\
`docker build -t pynb_final .`\
in order to build the docker image from the docker file.\
then run the command\
`docker run -v C:/Users/wahoo/Documents/STAT315/stat315final:/home/notebooks -p 8888:8888 --name python_notebook_final_report pynb_final`\
in order to build a container. make sure to replace `C:/Users/wahoo/Documents/STAT315/stat315final` with the path to this GitHub repository (since it contains the dockerfile)\
From here, copy one of the links from the terminal and paste it into a browser. You should be looking at a jupyter notebook file directory. Click on `notebook.ipynb` to access the python notebook. Then click Kernel > Restart Kernel and Run All Cells to see the entire proper report