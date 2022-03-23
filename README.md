# CSE_3244_Lab

## Overview
This is the lab for CSE 3244 | 25546 Spring 2022. 

## File Tree
```
- README.md
- main.py
- CSE3244_GCPLab_Overview.pdf
- images
- tasks
    task_one.py
    task_two.py
    task_three.py
    task_four.py
    task_five.py
    task_six.py
    task_seven.py
    task_eight.py
```

## Accounts

For this lab a GCP account was made with email cse3244osu@gmail.com and password 3244_osu. This account will be used for GCP.

## Useful commands

To start docker container (if it's not currently running)

```sudo docker run --hostname=quickstart.cloudera --privileged=true -t -i -v /home/cse3244osu/tmp:/src -p 8777:8888 -p 7190:7180 -p 90:80 721d222dcad0 /usr/bin/docker-quickstart -d```

or run 

```dockerun``` since the above command has been aliased in ~/.bashrc

To save mysql state into file

```sudo mysqldump -u root -p tennis > /src/mysql_dump.sql```

## Task One
[Answers](./tasks/task_one.txt)

![alt text](./images/Task_One.png "Task One Complete")

## Task Two
[Answers](./tasks/task_two.txt)
![alt text](./images/Task_Two.png "Task Two Complete")

## Task Three
[Answers](./tasks/task_three.txt)
    
## Authors

- [Benjamin Hobson](mailto:hobson.89@osu.edu)
- Bobby Spech
- Samuel Mahle