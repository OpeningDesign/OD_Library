 ### Revit Specific
 
- Try not to use the following, if possible...
	1. Dumb text notes. Prioritize the following instead.
		- 1st priority: Material Tags
		- 2nd priority: "OD_Keynote_Text Only" generic annotation
		- 3rd priority: dumb text
	2. Detail Lines and Detail Items. 
		- Use 3D objects as much as possible
	3. override graphics view by element
		- use Visibility/Graphic Overrides for Categories instead, or better yet, use View Templates
	4. Paint a material on an object. (apply a material via a type, or to entire object)

---

### FreeCAD Specific

- Export IFC files very soon and very often, test them in [IFC++](https://ifcquery.com/) first, then in Revit. Detect issues early
- Use simple extrusions as much as possible (Arch Wall/Structures/Panels or Part Extrude)
- Objects exported as IFC structural elements (beams, columns) often give problems in Revit. If needed, use BuildingElement Proxies (Will come as generic models, Revit won't apply any transformation on them)
- Keep list of materials clean, merge duplicates, make sure all objects have a material

---

### File Management on Windows

 - download favorite text editor
	 - example: https://atom.io/
		 - run as admin
 - Download and install https://gitforwindows.org/
   - Download the executable Git file from git-scm.com/download
   - Run the installation file with Administrator rights
   - Choose an appropriate installation location such as C:\_tools\git
   - Install the default components, including Git GUI Here and Git Bash Here
   - Choose default location of 'start menu folder'
   - Choose your preferred Git default editor.
	   - For example, choose Atom.io, if that's your preferred, and installed text editor.
   - Choose recommended 'path environment'
   - use openSSL library
   - Accept the default line ending conversion for Unix and Windows compatibility
   - Use MinTTY
   - Default (fast-forward or merge)
   - Extra options
	   - Enable file system caching
	   - Enable GIT Credential Manager
   - Click Finish to complete the install.
   - After Install
	 - Set longpath on windows 
		- Long answer: https://www.youtube.com/watch?v=mAGQZ7RvKFk
			- Short answer: Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem
				- Set LongPathsEnabled
					- Value data: 1

	 - Run **Git Bash** in administrator mode, like [this](https://www.dropbox.com/s/wk3l5weh1pt70oh/3TOLBa3Rs0.mp4?dl=0) and do the following 3 commands.  Do them in the exact following order.
		- `git config --system core.longpaths true`
			- Long answer [here](https://stackoverflow.com/questions/22575662/filename-too-long-in-git-for-windows/22575737#22575737)
		- `git config --system --unset core.autocrlf`
		- `git config --global core.autocrlf true`

  - Download and install https://tortoisegit.org/download/
	  - TortoiseGitPlink based on PuTTY...
	  - choose defaults
	  - First startup wizard
		  - Language
		  - Point to git.exe (probably will default to the proper location)
		  - Configure user information
			  - add name and email
		  - Authentication and credential store
			  - choose defaults
 - Install [gpg4win](https://www.gpg4win.org/download.html) with admin privileges
	 - choose default components
 - Create a github account: https://github.com/join
 - Download and install https://desktop.github.com/



---

### Creating a New Revit Family

1. When creating a new revit family, one of the cardinal rules when making families is that the objects should be constained to reference planes. 
2. There might be exceptions, but another cardinal rule is to start with a family template of the thing you're modeling... that is, use awindow template for windows, door template for doors, etc. 


---

### File too large to push to Github
If your file ever gets above 100mbs and you can't push to Github, try...
    

    
[](https://matrix.to/#/!uiaTztjLjbfSXeuBkn:matrix.org/$1560980161377209qhDgq:matrix.org?via=matrix.org)
    

 1. Purge all.  Run this (3) times to fully purge everything.

   ![image.png](https://matrix.org/_matrix/media/r0/thumbnail/matrix.org/XwGzEppwEgvdMOxuDrSTUxde?width=800&height=600)
 
2. For whatever reason, if you do a 'save as' to a temporary file name, and do another 'save as' to overwrite the original file. it reduces the file size.


---

### Random Errors

- If warnings..
  - warning: LF will be replaced by CRLF. 
	- Solution
		1. `git config --system --unset core.autocrlf`
		2. `git config --global core.autocrlf true`


  - clean filter git crypt failed
	  - https://github.com/AGWA/git-crypt/issues/184#issuecomment-541942913




C:\Users\ryan\.gnupg




- Git bash Error: Could not fork child process: 
	- https://stackoverflow.com/questions/45799650/git-bash-error-could-not-fork-child-process-there-are-no-available-terminals/
	- kill the 'agent' process that you last used.
		- might be: gpg-agent.exe



- To reset harder!
	- https://stackoverflow.com/a/4327720

- Buffer error
	- RPC failed; HTTP 524 curl 22 The requested URL returned error: 524 fatal: the remote end hung up unexpectedly: https://confluence.atlassian.com/bitbucketserverkb/git-push-fails-fatal-the-remote-end-hung-up-unexpectedly-779171796.html
		- `git config --global http.postBuffer 157286400`



- [rm -f .git/index.lock](https://stackoverflow.com/questions/9282632/git-index-lock-file-exists-when-i-try-to-commit-but-cannot-delete-the-file/11466435#11466435)

- assume-unchanged and skip-worktree flags
	- https://fallengamer.livejournal.com/93321.html
	- Usually: 


- Record audio and mic on ShareX: https://softwarerecs.stackexchange.com/questions/42767/screen-recording-tool-that-records-both-speaker-o-p-as-well-as-mic-input/74728#74728
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2MTg1NTAwMTAsMTc5OTg4MTQ0OCw5Mz
kxODQ5NDQsODIzMDA3MzU1LDEyMTcxMjU1MzMsLTEyMjk1NjI1
OTAsLTc5NzcyMzczNywxMTkxMTA0ODY0LC0xNzI2MDY3Njg5LC
0zOTg1MzE0ODYsLTE5NzU0Mjg4NTAsLTgyOTA4NzI3NywtNjQ5
MDcyOTI0LDEzMTc1OTAxMjYsLTg4MTUwNzc3LDE1MDY1NzE2ND
gsMzY1NTA1NjE2LDYzOTkwOTAwNSwxMjYyMzA0ODY0LDEzMDky
OTc5ODRdfQ==
-->