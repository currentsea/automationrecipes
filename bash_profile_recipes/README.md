# Bash Recipes to improve your profile 
# Usage: add a line like the one below to your bash profile and resource it 
```
* This will add the recipe to your terminal 

* Please don't mess with your terminal unless you know what you are doing or are prepared to deal with the consequences
# IF YOU DONT KNOW WHAT YOU'RE DOING, YOU CAN FUCK UP YOUR TERMINAL BEYOND REPAIR, so don't say i haven't warned you. 

# READING THE BELOW LINE IS PROBABLY IMPORTANT 

* `.bash_profile` may need to be replaced with your profiles filename, sometimes it is also `.bashrc`

# HOW TO APPLY A SINGLE RECIPE 

```
# $desired_recipe_file is the name of the recipe file you wish to include
$ echo "source $desired_recipe_file >> $HOME/.bash_profile"
```

* Source the new bash profile (which sources the recipe you downloaded)
```
source $HOME/.bash_profile 
```
