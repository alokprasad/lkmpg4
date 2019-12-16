Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@alokprasad 
1
10alokprasad/lkmpg4
 Code Issues 0 Pull requests 0 Actions Projects 0 Wiki Security Insights Settings
lkmpg4
/
lkmpg4.org
 

1
#+TITLE: The Linux Kernel Module Programming Guide
2
#+AUTHOR: Peter Jay Salzman, Michael Burian, Ori Pomerantz, Bob Mottram ,Alok Prasad
3
#+KEYWORDS: linux, kernel, kernel module, kernel programming
4
#+DESCRIPTION: How to make kernel modules for Linux
5
#+OPTIONS: ^:nil
6
​
7
​
8
​
9
* Introduction
10
The Linux Kernel Module Programming Guide is a free book; you may reproduce and/or modify it under the terms of the Open Software License, version 3.0.
11
​
12
This book is distributed in the hope it will be useful, but without any warranty, without even the implied warranty of merchantability or fitness for a particular purpose.
13
​
14
The author encourages wide distribution of this book for personal or commercial use, provided the above copyright notice remains intact and the method adheres to the provisions of the Open Software License. In summary, you may copy and distribute this book free of charge or for a profit. No explicit permission is required from the author for reproduction of this book in any medium, physical or electronic.
15
​
16
Derivative works and translations of this document must be placed under the Open Software License, and the original copyright notice must remain intact. If you have contributed new material to this book, you must make the material and source code available for your revisions. Please make revisions and updates available directly to the document maintainer, Peter Jay Salzman <p@dirac.org>. This will allow for the merging of updates and provide consistent revisions to the Linux community.
17
​
18
If you publish or distribute this book commercially, donations, royalties, and/or printed copies are greatly appreciated by the author and the [[http://www.tldp.org][Linux Documentation Project]] (LDP). Contributing in this way shows your support for free software and the LDP. If you have questions or comments, please contact the address above.
19
​
20
  
21
** Authorship
22
​
23
The Linux Kernel Module Programming Guide was originally written for the 2.2 kernels by Ori Pomerantz. Eventually, Ori no longer had time to maintain the document. After all, the Linux kernel is a fast moving target. Peter Jay Salzman took over maintenance and updated it for the 2.4 kernels. Eventually, Peter no longer had time to follow developments with the 2.6 kernel, so Michael Burian became a co-maintainer to update the document for the 2.6 kernels.  Bob Mottram updated the examples for 3.8 and later kernels, added the sysfs chapter and modified or updated other chapters.Alok Prasad forked Bob work to Further simplify the document and Added few more chapters
24
for better understanding of kernel programming.
25
​
26
** Versioning and Notes
27
​
28
The Linux kernel is a moving target. There has always been a question whether the LKMPG should remove deprecated information or keep it around for historical sake. Michael Burian and I decided to create a new branch of the LKMPG for each new stable kernel version. So version LKMPG 4.14.x(4.14.10) will address Linux kernel 4.12.x and LKMPG 2.6.x will address Linux kernel 2.6. No attempt will be made to archive historical information; a person wishing this information should read the appropriately versioned LKMPG.
29
​
30
The source code and discussions should apply to most architectures, but I can't promise anything.
31
​
32
** Acknowledgements
33
​
34
The following people have contributed corrections or good suggestions: Ignacio Martin, David Porter, Daniele Paolo Scarpazza, Dimo Velev, Francois Audeon, Horst Schirmeier, Bob Mottram and Roman Lakeev.
35
​
36
** What Is A Kernel Module?
@alokprasad
Commit changes
Commit summary
Update lkmpg4.org
Optional extended description
Add an optional extended description…
 Commit directly to the master branch.
 Create a new branch for this commit and start a pull request. Learn more about pull requests.
 
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
