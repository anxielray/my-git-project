# <font color="gree">GIT</font>

## _*Getting Started with Git*_

### _Initializing a New Repository_

- To initialize a new Git repository, navigate to the directory, in this case it is ``hello/`` and run the following command:

```bash
git init
```
    
- This will create a new directory named .git in your current directory, which contains all the necessary files and settings for your Git repository.
- Similarly other files will be created, files such as;

    - An empty commit with a SHA-1 hash

    - HEAD file, which points to the master branch

    - A ``.gitignore`` file.

    - A ``objects/`` directory which stores; ``blobs, trees and commits``.

    - A ``refs/`` directory; store pointers to ther commit objectsfor branches and tags.

### _First Script_

- In our shell script we have our "Hello, World" script and this is the out put when run using the following command;

command:
```bash
./hello.sh
```
or 

```bash
bash hello.sh
```

- This is if we don't want to use the shebang

Output :

```
Hello, World
```

### _*Git Status*_

- At this point the working tree is clean since nothing has been commited yet. We can confirm this by running the command;

```bash
git status
```


