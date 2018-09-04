
# MergeAndRemote
https://github.com/Bearcat202020/MergeAndRemote
**Q1- What does clone set the variable origin to represent?**

##clone sets origin to represent the remote repo that one wants to track##

**Q2- What does the command git push --set-upstream origin master do?**

##What does remote tracking mean in this context?##
:sparkles:

##it sets the origin variable a specified url. The remote tracking means that the origin tracks the local repo##

**Q3-**:camel:

##It pulls from master and merges with the current checked out branch.##
##now the current branch is up to date with master.##

**Q4-**:rocket:

##No they aren't they are merged with masters commits##

**Q5-**:octocat:

##It is a merge, you still have the commit history##

**Q6-**:metal:

##It is still behind the remote##

**Q7-**

##It didnt delete locally on person B's machine.##

**Q8-**

# Branching Structure #
* commit 6c7cc711f9417b5aaa4d64333da03ec2a634f226
| Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
| Date:   Tue Sep 4 14:26:27 2018 -0600
|
|     edited file.txt
|
* commit 7f785be25f25d2e64313c1e18ae15ce805ec9f13
| Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
| Date:   Tue Sep 4 14:21:42 2018 -0600
|
|     updated readme
|   
*   commit f87cc6a99cfed1c55d161e175ada3c62144d2178
|\  Merge: 73468ed 662860e
| | Author: getsnug <vramsey20@kentdenver.org>
| | Date:   Fri Aug 31 08:57:59 2018 -0600
| |
| |     Merge pull request #1 from Bearcat202020/personB
| |     
| |     Person b
| |   
| *   commit 662860e9a92c2a149feccee121fa09e28e51a79d
| |\  Merge: 0996440 a88d344
