# Git Submodule Example

https://www.youtube.com/watch?v=UQvXst5I41I&t=196s


git submodule add https://github.com/chamlyidunil/common-utility.git common-utility
git add common-utility
git commint -m "adding submodule"


# Work on Submodule from inside main module. 
```
cd common-utility
Make some change
Push changes. 
```
# Add new changes. 
```
When you execute git status from parent project 
you will some thing like modified:   common-utility (new commits)
Now you can add reference to new changes by
git add common-utitliy
git commin -m ""
git pust -u origin master
```


# When First time clone project with submodule. 
```
to update submodules : git submodule update --init 
```

# Get update submodule with parent project
git pull --recurse-submodules


# Reset submodule to orginal reference
git submodule update -f --recursive


