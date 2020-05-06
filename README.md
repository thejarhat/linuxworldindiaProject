# linuxworldindiaProject
A repository to implement jenkins to automate the deplyment of the code from one of our branches to our testing environment which is implemented in docker and a second job that is watching the master branch will deploy the code onto the production environment which is also implemented on docker and is accessible to the client publicly or via tunneling if it is a local machine.
There should be another job that is overlooked by the QA team that will merge the dev branch to the master branch when required. 
