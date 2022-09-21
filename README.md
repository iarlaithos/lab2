# lab2

#!/bin/bash

password=”pass123”

echo “enter your password”; read input

if [ “$input” == $password ] ; then

     echo “password is correct”
     
else

     echo “wrong password entered”
     
fi
