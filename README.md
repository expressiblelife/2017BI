# 2017 BI

### HW_ Introduction to Cloud Computing
05/Dec/2017

Welcome to the world of cloud computing:) 

The world is rapidly changing. IT is literally everywhere and you can never escape from it, so you chose this path. After graduating the most nominated school in South Korea, you wish to apply for job positions in Singapore, your preferred position is data analyst of expertise in Business Intelligence. You wish to appeal HR managers but they are not willing to take an interview… Now it is time to show your ability. 

Most of employers wish to know whether you are ACTUALLY good at IT skills. The higher degree can prove your background, but it is not enough to cover all the requirements of the position. So you decided to send them how excellent you are by archiving your portfolio online so that the HR manager can see that you are the right person. 

<p style="text-align: center;">===== Description ====</p>

##### Mission: Be a DevOps Engineer.
What is DevOps? (https://en.wikipedia.org/wiki/DevOps)

##### Goal: Show your cloud portfolio board to the HR Manager exploiting the DevOps tools as following:
- Platform: Microsoft Azure
- OS: Virtual Machine deployed on MS Azure (Any kind, any version is OK)
- SCM Repository: GItHub 
- Container Repository: DockerHub
- IDE: Jupyter Notebook

### Steps:
#### 1. Cloud Server
- Make Azure account (https://azure.microsoft.com/)
- Deploy Free Virtual machine of Ubuntu Server
- Get the address of cloud server and access via terminal using ssh
- Get Free Cloud Server

#### 2. Source Code Management
- Make GitHub account
- Install Git to your cloud server (they may provide git by default)
- Fork this repository (https://github.com/laftworld/2017BI.git)
- Clone the forked repository to your cloud server (git clone …)

#### 3. Container
- Make DockerHub account
- Install Docker
- Pull container which contains Jupyter notebook (https://hub.docker.com/r/jupyter/all-spark-notebook/)
- Run docker
- Exit

#### 4. Run Docker on your cloned folder
- Run docker with volume share option (-v) via 8888 port
- Execute docker enter into the running container and Install new python package ‘pydicom’    [how to install: conda install pydicom]

#### 5. Show your Job
- Modify the file 'resume.ipynb'. The file contains a python code printing your name and student ID
- Fill the form and with your resume

#### 6. Publish Your Work
- add, commit, and push to the forked repository
- Fork the repository (https://github.com/laftworld/2017BI.git), write your name and student ID, commit, and send pull request to the HR Manager.
- Commit the Docker Image
- Push the image to your DockerHub repository




### Submission
- Fill the file 'resume.ipynb' which requires DockerHub ID, GitHub ID, Cloud server address and access token for the running jupyter notebook (containing your resume)
- Don’t forget sending pull request via GitHub (they will provide you Approval CODE)

- Due: 19/Dec/2017 00:00 (Schedule confirmation required)

### Scoring: You will get the score as following:
#### (+1) You submitted the application form   						
#### (+1) You have your DockerHub account
#### (+1) You have your GitHub account
#### (+1) You have sent the pull request to the HR Manager
#### (+1) You sent your Docker repository which contains your own commit log
#### (+1) You sent the address for your “running” jupyter notebook
#### (+1) You sent  pull request which contains your own commit log

<p style="text-align: center;">===== Questions on the HW ====</p>

#### Issue Claiming: https://github.com/laftworld/2017BI/issues
#### Prof. Mun Yi: munyi@kaist.ac.kr
#### HR Manager: laftworld@kaist.ac.kr




