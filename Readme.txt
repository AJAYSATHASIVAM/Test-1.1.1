# What is Version Control ?
	- Vc is system that recordes changes to a file or set of files
	- That you can recall specific version later. 
	- One of the most popular VCS tools was a sys called RCS.
	
# Why version control sys invoked?
	- Developers encounter two major Problems
	1. Many people’s version-control method of choice is to copy files into another directory.
		> it is also incredibly error prone.
		> easly forget which dir you're and accidentally in write to the wrong file.
	2. The next major issue that people encounter is that they need to collaborate with developers on other systems.
	
# Git Special?
	- The major difference between Git and any other VCS, most other systems store information as a list of file-based changes.
	- CVS store as a set of files and the changes made to each file over time
	- Git store as a series of snapshots of a miniature filesystem.
	- Git most operation only local files and resources to operate 
# The Three States
	> Modified ---> changed file but not commited to your db
	> staged  ----> marked a modified file in its current version 
	> committed ---> your local database store in cloude repositroy
===========================================================================
# Where is my Histroy ?
 - .git dir in folder
# Basic commends
 - git add filename
 - git commite -m "Your message"
 - check git status
# I tried Deleting My repository
 - I go my repository
 - click settings 
 - scroll down and i see dangerzone settings > find delete repository 
 - click show some warnings read carefully ? i accept and type username/repository and then enter
 - git hub ask password > enter > Ok > my repositroy totaly vanished 
