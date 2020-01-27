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

1. Create a github account: https://github.com/join
2. Download and install https://desktop.github.com/
3. Download and install https://tortoisegit.org/download/
4. Download and install https://gitforwindows.org/
	- choose all the default settings
5. Set longpath on windows 
	- Long answer: https://www.youtube.com/watch?v=mAGQZ7RvKFk
		- Short answer: Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem
			- Set LongPathsEnabled
				- Value data: 1

6. Run **Git Bash** in administrator mode, like [this](https://www.dropbox.com/s/wk3l5weh1pt70oh/3TOLBa3Rs0.mp4?dl=0) and do the following 3 commands.  Do them in the exact following order.
	- `git config --system core.longpaths true`
		- Long answer [here](https://stackoverflow.com/questions/22575662/filename-too-long-in-git-for-windows/22575737#22575737)
	- `git config --system --unset core.autocrlf`
	- `git config --global core.autocrlf true`












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



- To reset harder!
	- https://stackoverflow.com/a/4327720
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzY1NTA1NjE2LDYzOTkwOTAwNSwxMjYyMz
A0ODY0LDEzMDkyOTc5ODQsLTc1MjQwODM3NSwxNDk1NzY3MDMx
LC02NTA2OTUzMTUsMjA4NTM2NzQ4OSwtMTQ2NTMyNjMwNywtMj
AwNTkzOTUxOSwyMTI5ODY5NzIzLDE4NTA5MTk1NTUsLTE2MDU4
NjU3NDMsMTY3MjIzMzIwMSwxNjc1MzU3MDQwLC0xODg3MTI0Nj
g2LDEwNzYxMDk5MjQsNTY0Nzc4OTUzXX0=
-->