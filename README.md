# Recipes for each profile shown below

```# Recipe for switching between Java 7 and Java 8 via the terminal 
# USAGE: Replace JDK7HOME and JDK8 Home with the path of your JDK installations respectively 
# Save this file as something like ".switch_java_recipe_aliases" in your home directory 
# Add the following line to your bash profile to source this recipe on each terminal startup 
# $ echo "source ~/.switch_java_recipe_aliases" >> ~/.bash_profile && source ~/.bash_profile
# Once you have sourced the below commands in your shell, you can switch between java8 and java7 as shown below: 
$ usejdk8 // Switches to java 8 and sets $JAVA_HOME=$JDK8HOME 
# $ usejdk7 // Switches to java 7 and sets $JAVA_HOME=$JDK7HOME 
```