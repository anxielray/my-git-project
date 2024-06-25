# <font color="gree">GIT</font>

## _*Getting Started with Git*_

### _Initializing a New Repository_

- To initialize a new Git repository, navigate to the directory where you want to create your project and run the following command:

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
