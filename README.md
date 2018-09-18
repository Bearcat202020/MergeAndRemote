
# MergeAndRemote
https://github.com/Bearcat202020/MergeAndRemote
**Q1- What does clone set the variable origin to represent?**

## clone sets origin to represent the remote repo that one wants to track ##

**Q2- What does the command git push --set-upstream origin master do?**

## What does remote tracking mean in this context? ##
:sparkles:

## it sets the origin variable a specified url. The remote tracking means that the origin tracks the local repo ##

**Q3-**:camel:

## It pulls from master and merges with the current checked out branch. ##
## now the current branch is up to date with master. ##

**Q4-**:rocket:

## No they aren't they are merged with masters commits ##

**Q5-****:octocat:**

## It is a merge, you still have the commit history ##

**Q6-**:metal:

## It is still behind the remote ##

**Q7-**

## It didnt delete locally on person B's machine. ##

**Q8-**

# Branching Structure #
* commit 4a0006afec24ae25a02e8e4e8fd2225b8e5ecf66 (HEAD -> master)
| Author: Bearcat2020 <jbarakat20@kentdenver.org>
| Date:   Tue Sep 4 14:52:10 2018 -0600
|
|     fixed readme probems
|
* commit 26bda5558be6982a9e03504af4674bdcc3ceec2f
| Author: Bearcat2020 <jbarakat20@kentdenver.org>
| Date:   Tue Sep 4 14:50:19 2018 -0600
|
|     added emojis to ReaadMe
|
*   commit 7b1675f0a77807b34014339c2eefd9f4a08e4476
|\  Merge: 5e562e2 2b11d3f
| | Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
| | Date:   Tue Sep 4 14:45:26 2018 -0600
| |
| |     Merge branch 'master' of https://github.com/Bearcat202020/MergeAndRemote
| |
| *   commit 2b11d3ffbd4a6e7e25870b57c9d60af4ec1c6e6e
| |\  Merge: f45a2fc cf21a78
| | | Author: getsnug <vramsey20@kentdenver.org>
| | | Date:   Tue Sep 4 14:35:05 2018 -0600
| | |
| | |     Merge pull request #2 from Bearcat202020/Feature2
| | |
| | |     edited file.txt
| | |
| | *   commit cf21a783f792092f1b3ebafa0285bd26da513faa
| | |\  Merge: 6c7cc71 f45a2fc
| | |/  Author: getsnug <vramsey20@kentdenver.org>
| |/|   Date:   Tue Sep 4 14:32:43 2018 -0600
| | |
| | |       Merge branch 'master' into Feature2
| | |
| * |   commit f45a2fc093f14ce0ff2b81c7b1a16882130c785c
| |\ \  Merge: 1070c89 7f785be
| | | | Author: Bearcat2020 <jbarakat20@kentdenver.org>
| | | | Date:   Tue Sep 4 14:29:26 2018 -0600
| | | |
| | | |     Merge branch 'master' of https://github.com/Bearcat202020/MergeAndRemote
| | | |
| * | | commit 1070c8922e6b379619a6a0af69da0157b143abb3
| | | | Author: Bearcat2020 <jbarakat20@kentdenver.org>
| | | | Date:   Tue Sep 4 14:28:24 2018 -0600
| | | |
| | | |     editted the same text that Vaughn did
| | | |
| | | * commit 6c7cc711f9417b5aaa4d64333da03ec2a634f226
| | |/  Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
| | |   Date:   Tue Sep 4 14:26:27 2018 -0600
| | |
| | |       edited file.txt
| | |
* | | commit 5e562e2954975f9cbc2dca835a8b9caa04b4ee62
| |/  Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
|/|   Date:   Tue Sep 4 14:45:05 2018 -0600
| |
| |       formatted readme
| |
* | commit 7f785be25f25d2e64313c1e18ae15ce805ec9f13
| | Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
| | Date:   Tue Sep 4 14:21:42 2018 -0600
| |
| |     updated readme
| |
* |   commit f87cc6a99cfed1c55d161e175ada3c62144d2178
|\ \  Merge: 73468ed 662860e
| | | Author: getsnug <vramsey20@kentdenver.org>
| | | Date:   Fri Aug 31 08:57:59 2018 -0600
| | |
| | |     Merge pull request #1 from Bearcat202020/personB
| | |
| | |     Person b
| | |
| * |   commit 662860e9a92c2a149feccee121fa09e28e51a79d
| |\ \  Merge: 0996440 a88d344
| | |/  Author: Bearcat2020 <jbarakat20@kentdenver.org>
| | |   Date:   Fri Aug 31 08:37:56 2018 -0600
| | |
| | |       Merge branch 'master' of https://github.com/Bearcat202020/MergeAndRemote into personB
| | |
| * | commit 0996440c51087fee559c096d2bb62c13e6624d03
| | | Author: Bearcat2020 <jbarakat20@kentdenver.org>
| | | Date:   Fri Aug 31 08:35:13 2018 -0600
| | |
| | |     added my own file for personB
| | |
* | | commit 73468eda1b22fbf2d4364ed751f4d5280d9add2c
| |/  Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
|/|   Date:   Fri Aug 31 08:48:54 2018 -0600
| |
| |       Updated readme
| |
* | commit a88d3441b9b176e36e8f985ad2adbcab1325c785
| | Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
| | Date:   Fri Aug 31 08:32:33 2018 -0600
| |
| |     edited file.txt
| |
* | commit 1d69349b7a4574ad0eca2105af8cc1a44841605c
|/  Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
|   Date:   Fri Aug 31 08:31:09 2018 -0600
|
|       answered first 2 questions
|
* commit 2c66c8a3c03190394e191fd0446ac1062526a1e8
| Author: Vaughn Ramsey <vramsey20@slp-vramsey20.local>
| Date:   Fri Aug 31 08:25:02 2018 -0600
|
|     Added file
|
* commit dc9f4832a1fc67455a1ef8ac47e153cafea7153c
  Author: Bearcat202020 <jbarakat20@kentdenver.org>
  Date:   Fri Aug 31 08:08:04 2018 -0600

      Initial commit
