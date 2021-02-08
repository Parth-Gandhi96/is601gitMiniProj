## Explain how the usage of Git, Docker, automated testing, and continuous integration can improve the productivity and competitiveness of a company:

### Git:
Git is a distributed version-control system for tracking changes and designed for coordinating work among programmers cooperating on source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows. Parallel Development and collaborative environment provided by git increases the productivity and rapidness of development team in organisation. 

**For more information about Git and Version control**

- https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control


### Docker:
Docker Container is software tool which contains source code and its required enviroment including the dependacies needed for every stages till the execution of code. It is lightweight package which can be deployed without worrying about application requirements, makes deployemnt process very easy. The key advantages of Docker containerization are - Portability, Performance, Agility, Scalablity and Isolation.

#### Advantages of Docker:

* Portability : 
No need for particular Operating system, only needs docker running. All the depnadanciess for succesful execution of code and libraries with required external packages are alreaady included in docker.


* Performance : 
VM (Virtual Machines) are another option for container, they are heavy-weight, they contains whole operating system. Whereas docker container runs on very smaller footprint compared to VMs, which makes them quicker to create and start - improveed performance.

* Agility : 
More agile and responsive to changes, because of the Light-weight in nature and portability taht it provides. 

* Isolation : 
Differnet Docker containers are totally independant of each other, the source code and packages included inside containers are totally isolated from outside environment. It is for sure, that Docker image is going to perform same as it did in development and testing process.


* Scalability : 
Quick creation and adding new functionality in same container is easy and smooth, which makes you deployed application scalable.

**For more information about Docker**
- https://www.microfocus.com/documentation/enterprise-developer/ed40pu5/ETS-help/GUID-F5BDACC7-6F0E-4EBB-9F62-E0046D8CCF1B.html
- https://www.docker.com/resources/what-container

### Automated Testing:
Automated testing is done through an automation tool, so more time can be spent on higher value tasks, such as exploratory tests while automating time-consuming tests, such as regression tests.  While you do need spend time maintaining test scripts overall, you will increase your test coverage and scalability. Automated testing is well-suited for large projects, projects that require testing the same areas over and over, which is usually a case in company's product because there are development going on for multiple features parallely and developers constantly updates the source code.Test automation increases overall software efficiency and ensures robust software quality

### Continuous integration:
It involves multiple steps before integrating the changes commited by developers into the shared code of product. The steps involves- identifing the changes, building the whole source code including the update, running test cases and finally generating the status report, if all successful then report also include the performance of code after integration and quality of the new source code. This way any new update on source code for product will be safe and continuously in check before integrating it to the final version of code. Nowadays it is almost very common pratice in any company that has development department.
**For more information about Continuous integration**

- https://www.katalon.com/resources-center/blog/ci-cd-introduction/
- https://www.katalon.com/resources-center/blog/benefits-continuous-integration-delivery/
