## research_track2_assignment_1 ##

# Description #

The aim of this project to be able to use the Sphinx for explaining a project. Research Track-1 second assignment tried to document by using Sphinx. In the project which is done in first semester, it has totally six ROS nodes, the three of them were given which are; go_to_point_service.py, wall_follow_serviece.py and bug_as.py three of them created by myself which are; action_usr.py, printer.py, service_goal.py. 

Depends on to the syntax of the Sphinx inside of the python files related descriptions had been done. The descriptions generally includes aim of the node and important connections of the node, like publishers, subscribers, clients, messages and their purposes for the communication.

After making changes inside of the script files, by going to the project folder inside of the terminal and by commanding this line: make html the html file had been created inside of the build folder. Inside of the html folder index.html should be visible. By clicking the index.html the sphinx web page must be visible. 


# Installing #

```bash
$(sudo) apt-get install python3-sphinx
```
```bash
$ pip3 install breathe
```

```bash
$ pip3 install sphinx-rtd-theme
```

```bash
$ sphinx-quickstart
```

# Running #


```bash
cd assignment_2_2022/build/html 
```
and click to the `index.html`
