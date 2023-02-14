# Scripts/Answers for ALX Project 0x03. Shell, init files, variables and expansions

## alias ls="rm *" - This Script will create an alias wth name ls and value rm *.

## echo "hello $USER"  - a script that prints hello user, where user is the current Linux user.

## export PATH=$PATH:/action  - A script that adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

## echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))  - a script that counts the number of directories in the PATH.

## printenv - a script that lists environment variables.

## set  - a script that lists all local variables and environment variables, and functions.

## BEST="School"  - a script that creates a new local variable with "BEST" as the name and "School" as the variable.

## export BEST="School"  -  a script that creates a new global variable. with "BEST" as the name and "School" as the variable.

## echo $(($TRUEKNOWLEDGE + 128))  -  a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

## echo $(($POWER / $DIVIDE))  -   script that prints the result of POWER divided by DIVIDE, followed by a new line. Here POWER and DIVIDE are environment variables.

## echo $(($BREATH**$LOVE)) - a script that displays the result of BREATH to the power LOVE. Here BREATH and LOVE are environment variables. The script displays the result, followed by a new line.

##      
