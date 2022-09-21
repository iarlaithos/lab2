# lab2

#!/bin/bash

args=(“$@”)

if [ ${args[0]} -eq ${args[1]} ] ; 
then
     echo “variables are the same”
else
     echo “variables are not the same”
fi
