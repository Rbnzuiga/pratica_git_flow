# pratica_git_flow
Rama development
Esta es la rama features 

In the beginning to generate an ssh key, use the following command: $ ssh-keygen -t rsa -b 4096 -C "your_email@example.com". Which sends us the following line in the terminal Enter a file in which to save the key (/c/Users/you/.ssh/id_rsa):[Press enter] that only tells us to put a name to the generated key or just hit enter to leave the default name.
then we must execute it and add our new key with the following commands:

$ eval $ (ssh-agent -s)
$ ssh-add ~ / .ssh / id_rsa

To clone our repository we will only use the command
git clone "address of our repository with ssh key"

we can check its status with a git status

followed by that we create a new branch with
git branch "name of the new branch"
we do a checkout to position ourselves in the new branch called develpment
followed by that by modifying the readme file we can do a git add. to load all the changes made and later make a new commit from the develpment branch
and to finish a git push

to generate the next branch, generate new content in the readme and commit was the same procedure as above but using the name features for the other branch.
