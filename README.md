# Project Terminus

Formerly Standard SDK Tests.

This project enables the manual execution, via GitHub Actions, of individual or multiple language SDK tests.

To run the tests do the following:

Click on the Actions tab highlighted below

![image-01](img/image-01.png)

Click on Execute Project Terminus in the left hand panel highlithed below

![image-02](img/image-02.png)

On the next screen click on Run workflow.

This will then display a drop down with run options. The Node build repo option defines the branch to build the NCTL Docker image from. If the action cannot locate the Docker image in docker.io then the image will be built by the action runner. Populate the blank language SDK fields with the desired branch to test. See the example below.

![image-03](img/image-03.png)

