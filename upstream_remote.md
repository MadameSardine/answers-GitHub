# A: an "upstream" remote is usually used when several people collaborate on the same Git project.

In order to minimize the chances of introducing mistakes in the common project, and allow every team member to work on the project without interfering with the work of other people, each person works on his/her version of the project on his/her local repository.

A remote is used to link two repositories. Thus, remotes are great tools to enable people to share their work. 

Remote repositories are versions of the project saved somewhere else (e.g. Internet, another computer, a server).

When someone wants to share some changes/additions made to the project, he/she has to push them "upstream" with the command: git push origin master.
