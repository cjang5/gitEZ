#gitEZ - *"git easy"*

##Installation
The simplest way to use this script would be to create a submodule with git in your repo directory
    git submodule add https://github.com/cjang5/gitEZ.git

You can then use a C compiler of your choice to compile the gitEZ.c file

    cd gitEZ

    clang gitEZ.c -o gitEZ

##Usage
You can then run the script from your repo folder with your commit message in double quotes!

    gitEZ/gitEZ "Initial commit"

    gitEZ/gitEZ "Fixed various bugs"

    gitEZ/gitEZ "Pls work"

That's it! It's as simple as that.

##Things to consider
gitEZ runs these commands for you

    git add --all

    git commit -m <MESSAGE>

    git push

So if you want to exclude some files from your git commit, **don't** use gitEZ!