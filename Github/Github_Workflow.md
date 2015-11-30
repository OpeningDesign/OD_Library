
####Before any of the steps below, please install [Github's Desktop Client](https://desktop.github.com/) to your local machine....

---
##Download (pull) from Cloud...Make Change...Upload (push) to Cloud

*If you own the repo or have permissions to modify the repo you would like to make changes to, you can do the following steps. If you do not, please follow the steps in the section called [Forking a Repo](#forking-a-repo).  After which you can do the following steps.*

1. From the Github Desktop client, click on the ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/image12.png) to ‘clone’ the specific repo to your local machine...*(fyi...some repos will take awhile to download, the first time)*<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_16-17-21.png)<br><br>
2. Choose the directory (folder) you wish to clone this repository to. 
	* (Word of caution: be caution of cloning the repo inside a Dropbox folder (or similar), as unfortunately the two don't play nicely with each other.)<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_16-18-32.png)<br><br>
3. Navigate via Windows to this newly created folder or right click on the repo name in the Github Client and 'Open in Explorer'<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_16-19-59.png)<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_16-44-29.png)<br><br>
4. Add file(s), and/or open and modify any file that you need. 
	- Don’t change a [blob file](https://en.wikipedia.org/wiki/Binary_large_object) (examples: .rvt, .dwg, .psd, etc.) that you know someone else is working on.  If you don’t know, ask on the Github issues, if you can work on a particular file.  
	- For [Markdown](https://en.wikipedia.org/wiki/Markdown) (.md) or any similar [plain text](https://en.wikipedia.org/wiki/Plain_text) files, you don't have to ask, as these can be developed concurrently in a distributed manner, and merged together at a later date.  This is where the power of Github really comes into play.  See [Making Changes to a Markdown File](#making-changes-to-a-markdown-file) section below.<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_16-45-51.png)<br><br>
5. <a name="step_5"></a>Go back to the Github client and fill in the ‘summary’ and ‘description' (optional) per the following example, and then click 'Commit to master'<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_16-48-33.png) <br><br>
6. then click ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_16-49-51.png), which will push these changes to the Github cloud.

> If you'd like to push this change to the original repo you forked from, you can follow the [Make Pull Request](#make-pull-request) section below


---

## Forking a Repo

 1. If you want to make a change to a repo that you don't own (or do not have permissions to change) you'll have to ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-15-00.png) the repo to your own account...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-15-25.png)<br><br>After which, it's cloned to... <br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-19-28.png)<br><br>
 2. At this point you can follow [Download (pull) from Cloud...Make Change...Upload (push) to Cloud](#download-pull-from-cloudmake-changeupload-push-to-cloud) section above


---

##Making Changes to a [Markdown](https://en.wikipedia.org/wiki/Markdown) File

You can modify the Markdown (.md) file one of the following two ways.

#### Method (1)

 1. Go to the repo site on Github. Navigate through the list of files/folders and click on the [markdown(.md)](https://en.wikipedia.org/wiki/Markdown) file you'd like to modify.<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-08-46.png)
 2. Click on![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-15-32.png) icon <br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-14-38.png)
 3. Edit the file in the space below...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-16-47.png)<br><br>flip to the ![enter image description here](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-30_07-12-15.png) to see how the markdown file is rendered... <br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-17-35.png)<br><br> 
 4. Once changes are made, fill in the following and 'commit changes'...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-23-23.png)


#### Method (2)

 1. You can also edit the Markdown file from a multitude of Markdown editors.  Showing how popular this format has become,  [here's](http://mashable.com/2013/06/24/markdown-tools/#y43cFmKIqqq3)  an exhaustive list of both web-based and desktop-based editors you could use.  My favorite is [StackEdit](stackedit.io/editor#). <br><br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-03-35.png)<br><br>
 2. After saving and making your changes, go to [Step 5](#step_5) in the [Download (pull) from Cloud...Make Change...Upload (push) to Cloud](#download-pull-from-cloudmake-changeupload-push-to-cloud) section above to commit your changes and pushing them to the cloud.


---

##Syncing file changes down from the Github cloud and viewing the 'diff' between versions.

 1. Go to the Github Client and click on ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-33-09.png) as seen below...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-31-01.png) <br><br> After syncing, the changes or history of commits will be viewable here.  The text highlighted in green below shows what was added.  The text highlighted in red shows what was deleted or changed... <br><br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-31-47.png)<br><br> You can also go to the github website to see the history of changes and diffs between file versions.  Click on 'commits' below...<br><br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-36-42.png)<br><br>From the list, click on the commit or versions you'd like to see the diff on....<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-38-09.png)<br><br>The text highlighted in green below shows what was added.  The text highlighted in red shows what was deleted or changed...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_17-38-36.png)






---
 
## Make Pull Request

*If you'd like to push a change to a repo you forked from, do the following.  The user, however, who owns the repo (or has permssions) has to accept the pull request.  See [Accepting the Pull Request](#accepting-the-pull-request) below.*

 1. List item![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-34-54.png)<br><br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-35-33.png)<br><br>
 2. After clicking on ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-34-54.png) you will see the following<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-39-44.png)<br><br>The left pull down menu...<br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-41-47.png)<br>...is where the changes are going, the right menu....<br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-41-52.png) <br>...is where the changes are coming from.<br><br>
 3. Leave optional comment. If everything looks okay click on ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-39-49.png) <br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-48-15.png)

<br><br>

---
## Accepting the Pull Request

 1. By clicking on the ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-55-11.png) tab you can see a list of pull requests.  After which click on the pull request you'd like to accept. <br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-49-27.png)
 2. Click on 'Merge pull request'... <br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-52-19.png)<br><br>
 3. The 'confirm merge'... <br><br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_18-56-11.png)


---

## Pulling changes from another repo
1. To view if there's any other additional changes in any of the other related cloned repos go to ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-36-45.png) --> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-36-50.png) As you can see from the network graph below, osciawilson's repo had (1) change ahead of the OpeningDesign repo...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-36-58.png)<br><br>
2. Go to the repo you wish to pull the changes from and click 'New pull request'...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-45-29.png)<br><br>
3. If nothing appears for comparison, click on 'compare across forks' <br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-45-44.png)<br><br>Should look something like this...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-46-14.png)<br><br>The left pull down menu...<br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-48-16.png)<br>...is where the changes are going, the right menu....<br> ![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-48-23.png) <br>...is where the changes are coming from.<br><br>
4. Fill in the following and click on 'Create pull request'...<br><br>![](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_19-48-51.png)<br><br>
5. click on 'Merge pull request'... <br><br>![enter image description here](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_20-03-04.png)<br><br>
6. click on 'Confirm merge'...<br><br>![enter image description here](https://dl.dropboxusercontent.com/u/7117445/Screencaptures/2015-11-29_20-03-14.png)


<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
