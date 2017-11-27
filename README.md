# 2017 BI

## HW_ Introduction to Cloud Computing
05/Dec/2017

Welcome to the world of cloud computing:) 

The world is rapidly changing. IT is literally everywhere and you can never escape from it. You were passionate on IT trend so you chose this path. After graduating the most nominated school in South Korea, you wish to apply for job positions in Singapore, your preferred position is data analyst of expertise in Business Intelligence. You naively contacted HR managers but they are not even willing to take an interview… Now it is time to show your ability. 

Most of the employers wish to figure out whether you are ACTUALLY good at IT skills. The higher degree can helpful to prove your background, but it is not enough to cover all the requirements of the position. So you decided to show them how excellent you are by archiving your portfolio online so that the HR manager can see that you are the right person. 

### Description

#### Mission: Be a DevOps Engineer.
What is DevOps? (https://en.wikipedia.org/wiki/DevOps)

#### Goal: Show your portfolio board on cloud with the DevOps tools as following:
- Cloud Platform: Microsoft Azure
- OS: Virtual Machine deployed on MS Azure (Any kind, any version is OK)
- SCM Repository: GItHub 
- Container Repository: DockerHub
- IDE: Jupyter Notebook

#### Steps:
##### 1. Cloud Server
- Sign up MS Azure (https://azure.microsoft.com/).
- Deploy free VM (virtual machine).
- Access to the VM via ssh.
- Take a note of your access information **(VM address, id, password)**.

##### 2. Source Code Management
- Sign up GitHub (https://www.github.com/).
- Fork the repository (https://github.com/laftworld/2017BI.git) into your account.
- Install Git to your VM (the VM may provide git by default).
- Clone the forked repository into your VM `git clone …`.
- Take a note of your GitHub information **(repository address)**.

##### 3. Container
- Sign up DockerHub (https://hub.docker.com/).
- Install Docker to your VM.
- Pull the container (https://hub.docker.com/r/jupyter/all-spark-notebook/) into your VM.

##### 4. Run Docker on Your Cloned Folder
- Run docker `docker run ...` with volume share option `(-v)` via 8888 port. So docker shares the Git-Cloned folder with VM.
- Enter into the running container `docker exec ...`.
- Enter inside the running docker enter into the running container and Install new python package ‘pydicom’ `conda install pydicom`.
- Commit the docker image `docker commit ...`.
- Push the docker image into your DockerHub repository `docker push ...`.
- Take a note of your Jupyter Notebook information **(access token)**.
- Take a note of your DockerHub information **(repository address)**.

##### 5. Show your Ability
- Open your web browser
- Access the Jupyter Notebook `https://VM-address:8888`.
- Insert the access token.
- Fill the blanks in the file 'resume.ipynb'.
- Code something to show your portfolio.

##### 6. Publish Your Work
- Use git `add`, `commit`, and `push` to the forked repository.
- Send pull request to the HR Manager. You need to 'compare across forks'.
- The HR Manager will provide you address of **submission form** and **approval code** (ex: 1407). Take note.
- The HR Manager will send you back anyway you fail to complete all the tasks above.

### Submission
- Submit the application form

### Due 
- 19/Dec/2017 00:00

### Scoring: You will get the score as following:
- (+5) You submitted the application form   						
- (+1) You have your DockerHub repository
- (+1) You have your GitHub repository
- (+1) You sent the access information of your “running” jupyter notebook
- (+1) You sent the access information of your VM
- (+1) You coded something of your own appealing to HR Manager

### Questions on the HW

- Issue Claiming: https://github.com/laftworld/2017BI/issues
- HR Manager: laftworld@kaist.ac.kr
- Prof. Mun Yi: munyi@kaist.ac.kr
