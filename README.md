# lab2

#!/bin/bash

echo “enter two numbers”

read -a args # the -a option reads input into an array

echo “what operation to perform? (+ - x / %)

read operation

case $operation in

     +) echo “$((${args[0]}+${args[1]}))” ;;

     -) echo “$((${args[0]}-${args[1]}))” ;;

     x) echo “$((${args[0]}*${args[1]}))” ;;

     /) echo “$((${args[0]}/${args[1]}))” ;;

     %) echo “$((${args[0]}%${args[1]}))” ;;

     *) echo “invalid choice of operator”
esac
