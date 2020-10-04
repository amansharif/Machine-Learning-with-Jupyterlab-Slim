# ML-Tutor
![FED UP!!!](fedup.png)

## Introduction
It's always fun to learn Machine Learning (ML). But setting up the environment is a tedious task and eats up a lot of time as well as energy. You need to install python, then libraries, dependencies, Jupyter etc. By the time you finish configuration you're exhausted. Isn't it true? But what if you don't need to do any of those? What if someone else takes care of those on behalf of you and you can enjoy Machine Learning? Sounds so Great. Right? Well, 'Docker' to the rescue! You just need to install 'Docker' on your machine and need not to worry about anything else. You can set up the environment and demolish any time you want. All of these is just a command away from you. The idea is to provide a configured environment so that teachers can focus on teaching and students can focus on learning.

## What you’ll get here?
- Configured Jupyter Lab (Image size 1.83 GB)
- Installed Libraries (Most of the ML libraries including tensorflow 2.3.0 for DL)
- No need to worry about dependencies
- Root privileges which means you can also install libraries if you want or required.
- Some public datasets
- Demo codes from almost all crucial ML concepts

## Prerequisite
- Only Docker  >= 19.03.12

## How to install Docker?
It’s pretty easy and straight forward process. Please visit the [link](https://docs.docker.com/docker-for-windows/install/)

## Steps to follow after docker installation

- First lets check docker is properly installed or not. Open your terminal and fire the below command.

'''docker version'''
  
  You should get the following output.

  ![](docker-version.png)

- Since docker is running perfectly now we can move to the second step. Fire the below command.

'''docker run -itd --rm -p 8080:8080 aman10/ml-tutor'''

![](docker-run.png)

- Now open your browser and copy paste the below URL and give password 'aman' when prompted.

'''http://host.docker.internal:8080'''

![](j-lab1.png)

Viola !!! Your Jupyter Notebook with all crucial ML codes organized to learn and practice.

**SUGGESTION:** Go through the codes chronologically.

![](j-lab2.png)

Enjoy Machine Learning

![](j-lab3.png)

## License