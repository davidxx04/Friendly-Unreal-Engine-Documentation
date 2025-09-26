# Set up

### First we have to install git lfs
The lfs (large file system) allows us to put large files on our repos, so we have to install them and then do this in git bash:
![[Pasted image 20250925130356.png]]


1. On bellow left -> version control -> connect

2. the we select provider: git (beta version) (i dont know if it´s still beta version)

3. mark all checkboxes
![[Pasted image 20250922163114.png]]

4. (also mark enable git lfs obviously)
5. click on Initialize project Git
6. Accept settings



# Github desktop 
Then we go to the desktop -> add existing repository -> select the game folder (unreal projects\somegame).

Then we go to the bash and do the following:
![[Pasted image 20250925130525.png]]
This way we put content on the repo with lfs, if we want to add something else we can do the same command again:
```
$ git cd project
$ git lfs track ".content"
```






# Commit
1. Revision control -> submit content

- If i change something, when I go to submit content I can check changes by clicking on the thing changed, then I can see what i have changed, the event graph and so on.
	![[Pasted image 20250922164441.png]]
	