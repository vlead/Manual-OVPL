Title:
Manual-OVPL

Description:
We are trying to manually host the labs following one vm per lab model. And making labs available on individual containers.
It involves following various interesting challenges that needs to be taken care of, when we automate the whole process of hosting through ovpl:-
a. Setting disk space for containers.
	Example: Depending on the lab size we need to set the container's disk space.
b. Setting RAM size.
c. Setting number of processes.
d. Package installation may take long time, and that needs to be taken care of.
	Example: Sage-server in database lab took 7 Hrs to get installed.
e. OS template to be used while creating containers.
	Example: Depending on the lab we need to select OS template. If a lab requires mysql we will choose the mysql customized template.


