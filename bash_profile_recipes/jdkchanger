#!/usr/bin/env bash
# Author: currentsea (admin@btcdata.org) 
# jdkhomechanger
# Recipe for switching between Java 7 and Java 8 via the terminal 
# USAGE: Replace JDK7HOME and JDK8 Home with the path of your JDK installations respectively 
# Save this file as something like ".jdkhomechanger" in your home directory 
# Add the following line to your bash profile to source this recipe on each terminal startup 
# $ echo "source ~/.jdkhomechanger" >> ~/.bash_profile && source ~/.bash_profile
# Once you have sourced the below commands in your shell, you can switch between java8 and java7 as shown below: 
# $ usejdk8 // Switches to java 8 and sets $JAVA_HOME=$JDK8HOME 
# $ usejdk7 // Switches to java 7 and sets $JAVA_HOME=$JDK7HOME 
export JDK7HOME="/Library/Java/JavaVirtualMachines/jdk1.7.0_79.jdk"
export JDK8HOME="/Library/Java/JavaVirtualMachines/jdk1.8.0_77.jdk" 
alias usejdk8="export JAVA_HOME=$JDK8HOME && echo \" JAVA 8 ($JAVA_HOME) IS NOW \$JAVA_HOME\""
alias usejdk7="export JAVA_HOME=$JDK7HOME && echo \" JAVA 7 ($JAVA_HOME) IS NOW \$JAVA_HOME\""
