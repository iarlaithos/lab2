# lab2

#!/bin/bash
args=(“$@”)
count=0
while [ $count -lt ${args[0]} ]; do
     echo “$count”
     ((count++))
done
