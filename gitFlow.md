## Git flow explanation

5 types of branches are important to understand inorder to understand the upper level flow of git:

- master

Production source code is directly connected with this branch of code.
So final source code wiht all developed feature planned and tested feature's code will be commited at this level
Only hotfixes and release branches can merge the code to master branch.

![image1](images/gitflow_4.PNG)

- hotfixes

Emergency bugs in the source code on master branch (could be deployed on production level), gets solved from this branch and it can got to develop and then feature branch if required.

![image2](images/gitflow_3.PNG)

- release branches

Any feature once finished developing and are ready according to planned will get pushed into release branch. From this relase branch a feature can go back to development due to failure in testing, so cycle of deploy->test->fix->deploy->retest gos on untill oit reaches the satisfaction level of requirements for release. Once it gets ready for release it merges the code with master.

![image3](images/gitflow_2.PNG)

- Develop & feature branches

Feature branches are branched off of the develop branch, and finished features and fixes are merged back into the develop branch when they’re ready for release. Feature branches will be of developing New features and non-emergency bug fixes.

![image4](images/gitflow_1.PNG)

### Key Benefits
* Parallel Development
* Collaboration
* Release Staging Area
* Support For Emergency Fixes

**For more Information on Git flow:**
https://datasift.github.io/gitflow/IntroducingGitFlow.html
