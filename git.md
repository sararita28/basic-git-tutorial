//Basic Commands

    $git init        //Iinitialize Local Git Repo (will create a .git folder in your project hidden by default)
    $git add <file>  // Add a file to the index
    $git rm <file>   // Remove a file to the index
    $git add *.html  // Add all html files to the index
    $git add .       // Add all files to the index
    $git status      // Check status of working tree (To see what you have in the index)
    $git commit      // Take everything in the index and put it in the local repo

    // The following commands have to do with remote repo (i.e github ...)
    $git push       // Push to remote repo (will need to add link to your remote repository account)
    $git pull       // Pull latest changes from remote repo
    $git clone      // Clone repository into your current folder

//Installing GIT

    Linux (Debian)  // $sudo apt-get i git
    Linux (Fedora)  // $sudo yum i git
    Mac             // http://git-scm.com/download/mac
    Windows         // http://git-scm.com/download/win

//Check if git is installed

    $git --version  // if a version number is returned then it's successfully installed

//Tutorial

    - Once github is installed and initialized, you want to add your name and email address to git so in your terminal you add these 2 lines of codes once at a time:
        $git config --global user.name 'YourName'
        $git config --global user.email 'YourEmail'

    - Then you can start adding files to your repo using $git add <filename.index>
    *Notice that while nothing happens when you enter these commands, it doesn't mean that nothing has changes. To check which files have been added to your repo you can use the command $git status

//Definition

    Changes not staged for commit  // Means that we've added changes to a file while it was in the staging area (so you must add it again with the updated changes. You do that with the same $git add <file> command)
