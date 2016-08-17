>Viewing a diff between two files helps indentifying areas where a new bug may
>have been introduced. So check those locations first when things are "suddenly"
>broken.

#Other notes:
**Use git-bash to get linux style command prompt**

**_on windows you have program called FC. Can be runned from commandline:_**
>	FC file-old.js file-new.js

#Reflect: Manual Commits
**_By committing manually instead of automatically, you can decide what to commit and when._**

**_This gives the opportunity to split the commits based on functionality._**

**_By committing manually you can specify commit messages describing what has changed, instead of only showing an auto commit._**

#Reflect: Multi-File commits
**_Multi-file commits are usefull when files are related to eachother._**

**_"Normal" documents seldom have relations, so those are not needed. In sourcecode, files will have lots of relations._**

**_So having multi-file commits is an essential feature._**


#Reflect: what do you want to try using Git for?
**_Source code for a simple website/game/video files editing/Opensource/Photoshop/many more use cases_**

#Commands:

>q |    exit git log!

>git log  |    List the commits and show which files have changed

>git log --stat  |    Show addition information about the commits

>git diff id1 id2  |    Compare two commits

>git clone  |    Create a local copy/clone from the repository

>git config --global color.ui auto |    get colored diff output

>git checkout  |    Shows a previous version of the file. This is not a checkout to edit like in SVN or TFS!
