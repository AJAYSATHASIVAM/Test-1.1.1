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
 ===============================================================================
 Today I learned git init command :
 
 
Creates the .git Directory:
	Running git init creates a hidden directory named .git in the root of your project. This directory is where Git stores all of its configuration files, metadata, and object database.

Initializes a New Repository:
	It marks the current directory and its subdirectories as the root of the Git repository. This means that the directory and its contents will be version-controlled.

Sets Up Initial Configurations:
	Git initializes some default configuration settings for the repository, such as the default branch name (master in older versions, or main in newer versions), user information, and other settings.

Prepares for Version Control:
		Git sets up the initial index and other internal data structures that it uses to track changes in your project over time.

Usage example:

bash
Copy code
cd /path/to/your/project
git init
 
 
 
