# Development File Directory - _Work in Progress_

**Background**: A clean and well organized file structure is the visual representation of a clean soul. I create my own projects, some of the projects should be kept longterm while others could/should probably be deleted. A prime example is video and book source code which I may never actually open, or look at the code once. Other times the code is modified and executed.

**Purpose**: Organize the file system to satisfy the following requirements
  - All the code should be available on the local machine as well as backed up to at least one online location
  - Situation: 
    - Developed on computer A, checked into Git on Computer A. Pushed to remote repository
    - Cloned on computer B from remote repository, modified on computer B, checked into Git and synced back to remote repository
    - If sync is used there is an issue when the code is modifed by both computers to store the working directory. Sync should only have the backup. Remote repository is used for file management
  
  - GoLong file structure is set up with best practices
  - Easy to know where to go to get what is being looked for
  - Easily adaptable but the base should serve for most situations
  - Folders and filenames should ideally be lowercase, works better with my lazy desire to not use capital letters

Workspace based off of GO - Using home folder instead
- username/dev/bin
- username/dev/pkg
- username/development/src
  - gh
    - journeyman32
        - repo_folder
        - _other repo/project folder_
    - _other github.com usernames_
  - gl _example for GitLab_
- username/dev/zips
- username/dev/lib
_