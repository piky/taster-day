# taster-day
Given tasks on taster-day at inet-logistic ltd.

### TASK01 : Building simple Docker container with Django and Python script ###
``` bash
cd task01
chmod a+x ./runme.py
docker build -t <author/taskname:tag> .
docker images
docker run -it <image_name> /code/runme.py
```

### TASK02 : List files from current working directory ####
``` bash
cd task02
chmod a+x ./list_files.py
./list_files.py
```