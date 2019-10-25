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

### FreeCAD Specific

- Export IFC files very soon and very often, test them in [IFC++](https://ifcquery.com/) first, then in Revit. Detect issues early
- Use simple extrusions as much as possible (Arch Wall/Structures/Panels or Part Extrude)
- Objects exported as IFC structural elements (beams, columns) often give problems in Revit. If needed, use BuildingElement Proxies (Will come as generic models, Revit won't apply any transformation on them)
- Keep list of materials clean, merge duplicates, make sure all objects have a material

### File Management

1. Create a github account: https://github.com/join
2. Download and install https://desktop.github.com/
3. install https://gitforwindows.org/
	- choose all the default settings
4. Set longpath on windows 
	- https://www.youtube.com/watch?v=mAGQZ7RvKFk
		- Short answer: Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem
			- Set LongPathsEnabled
				- Value data: 1

5. set longpath on git
	- https://stackoverflow.com/questions/22575662/filename-too-long-in-git-for-windows/22575737#22575737
		- Short answer: `git config --system core.longpaths true`







----------


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
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMDU5Mzk1MTksMjEyOTg2OTcyMywxOD
UwOTE5NTU1LC0xNjA1ODY1NzQzLDE2NzIyMzMyMDEsMTY3NTM1
NzA0MCwtMTg4NzEyNDY4NiwxMDc2MTA5OTI0LDU2NDc3ODk1M1
19
-->
