#gitEZ *"git easy"*

##Usage
Use a C compiler of your choice to compile the gitEZ.c file

    clang gitEZ.c -o gitEZ

    gcc gitEZ.c -o gitEZ

Execute the script with your commit message in double quotes!

    ./gitEZ "Initial commit"

    ./gitEZ "Fixed various bugs"

    ./gitEZ "Pls work"

That's it! It's as simple as that.

##Things to consider
gitEZ runs these commands for you

    git add --all

    git commit -m <MESSAGE>

    git push

So if you want to exclude some files from your git commit, **don't** use gitEZ!