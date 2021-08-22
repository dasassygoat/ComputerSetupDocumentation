# Windows File Directory - _Work in Progress_

Background: A clean and well organized file structure is desired. I create my own projects, some of the projects should be stored while others
probably could be deleted with no harm. I download source code and some of the source code I only use to look at the code and other times it is
used for modifications. 

Purpose: Organize the file system to satisfy the following requirements
  - All code should be available on the local machine as well as backed up
  - Situation: 
    - Developed on computer A, checked into Git on Computer A. Pushed to remote repository
    - Cloned on computer B from remote repository, modified on computer B, checked into Git and synced back to remote repository
    - If sync is used there is an issue if its used by both computers to store the working directory. Sync should only have the backup. Remote repository is used for file management
  
  - Go file structure is set up with best practices
  - Easy to know where to go to get what is being looked for
  - Easily adaptable but the base should serve for most situations
  - folders and filenames should ideally be lowercase, works better with my lazy desire to not use capital letters

Workspace based off of GO - Using D drive instead
- c:\development\bin
- c:\development\pkg
- c:\development\src
  - github.com
  - journeyman32
      - repo_folder
      - _other repo/project folder_
  - _other github.com usernames_
- c:\development\zips
- c:\development\lib
