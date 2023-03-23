<style>
r { color: Red }
b { color: Brown }
g { color: Green }
o { color: Orange }
bl {color: Blue}

</style>

<r>Git init</r><br/>
Go to a brand new folder and create a file and go to terminal and type ```git init``` <br/>
Once you do that you will notice the file will turn to green color in vscode. <br/>
And git icon will have one on it as shown below
![git intro](file:///D:/JOURNEY/Git/pics/01.jpg)
<br/>
Bottom left will show it as ```master``` meaning we are on main branch <br/>
![main branch](file:///D:/JOURNEY/Git/pics/02.jpg)

<br/>
By default, vscode hides the ```.git``` folder <br/>
To view it, go to <code>preferences>files.excluded</code> <br/>
<r>How to remove git from a project</r><br/>
As soon as you delete .git folder from your project, you can remove git from your project. <br/>

<r>How to add all files in current directory to staging area</r><br/>
Use the following command ```git add .``` <br/>
![unstaged](file:///D:/JOURNEY/Git/pics/03.jpg) <br/>

If you look at right side of Readme.md you can see ```U``` <br/>
It means file is ```unstaged``` <br/>

When you do ```git add .``` <br/>
You can see ```A``` on the right side of Readme.md <br/>
This means ```file is added to the tracking list``` <br/>
To make the files untracked again use the following command ```git reset .```
File is again ```shown as U on the right side of Readme.md``` <br/>
![reset command](file:///D:/JOURNEY/Git/pics/05.jpg) <br/>

<r>To add a single file to staging area</r><br/>
git add Readme.md <br/>
Now if you run ```git status``` command it will say one file to be committed as ```it tracks only Readme.md``` <br/>

<r>How to ignore files</r><br/>
There will be files or folders that we will not want git to track. <br/>
Go to <code>preferences>files.excluded</code> and remove ```**/.git``` <br/>
Then you will be able to see ```.git``` folder <br/>

Go to ```.git>info>exclude``` file and mention the file name that you do not want to track <br/>
Now if you type ```git status``` you will will see that git will not show ```secrets.json``` file and you will see that there is neither ```U or A``` icon to the right of ```secrets.json``` file. <br/>

<r>Git log</r><br/>
To see all the commits so far we use ```git log``` command <br/>


<r>If you make any changes to tracked files then that file will be shown as ```yellow``` in color</r><br/>
