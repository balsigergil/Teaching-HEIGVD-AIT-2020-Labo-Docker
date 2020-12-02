# Lab 4 - Report

> Authors: Gil Balsiger & Julien Béguin  
> Date: 02.12.2020

## Task 0: Identify issues and install the tools

### Questions

1. **[M1]**: 
1. **[M2]**: 
1. **[M3]**: 
1. **[M4]**: 
1. **[M5]**: 
1. **[M6]**: 

### Deliverables

> 1\. Take a screenshot of the stats page of HAProxy at http://192.168.42.42:1936. You should see your backend nodes.

![](./screens/screen01.png)

> 2\. Give the URL of your repository URL in the lab report.

https://github.com/balsigergil/Teaching-HEIGVD-AIT-2020-Labo-Docker forked from https://github.com/SoftEng-HEIGVD/Teaching-HEIGVD-AIT-2020-Labo-Docker

## Task 1: Add a process supervisor to run several processes

### Deliverables

> 1\. Take a screenshot of the stats page of HAProxy at http://192.168.42.42:1936. You should see your backend nodes. It should be really similar to the screenshot of the previous task.

![](./screens/screen02.png)

> 2\. Describe your difficulties for this task and your understanding of what is happening during this task. Explain in your own words why are we installing a process supervisor. Do not hesitate to do more research and to find more articles on that topic to illustrate the problem.



## Task 2: Add a tool to manage membership in the web server cluster

> Anyway, in our current solution, there is kind of misconception around the way we create the `Serf` cluster. In the deliverables, describe which problem exists with the current solution based on the previous explanations and remarks. Propose a solution to solve the issue.

### Deliverables

> 1. Provide the docker log output for each of the containers: `ha`, `s1` and `s2`. You need to create a folder `logs` in your repository to store the files separately from the lab report. For each lab task create a folder and name it using the task number. No need to create a folder when there are no logs.
>
>    Example:
>
>    ```
>    |-- root folder
>      |-- logs
>        |-- task 1
>        |-- task 3
>        |-- ...
>    ```
>
> 2. Give the answer to the question about the existing problem with the current solution.

Pas de problèmes lol

> 3. Give an explanation on how `Serf` is working. Read the official website to get more details about the `GOSSIP` protocol used in `Serf`. Try to find other solutions that can be used to solve similar situations where we need some auto-discovery mechanism.