# lab2

#!/bin/bash
# get arguments given by user
args=(“$@”)
let add=${args[0]}+${args[1]}
echo “${args[0]} + ${args[1]} = $add”
subtract=$((${args[0]}-${args[1]}))
echo “${args[0]} - ${args[1]} = $subtract”
multiply = $[${args[0]}*${args[1]}]
echo “${args[0]} * ${args[1]} = $multiply”
let divide=${args[0]}/${args[1]}
echo “${args[0]} / ${args[1]} = $divide”
modulus=$((${args[0]}%${args[1]}))
echo “${args[0]} % ${args[1]} = $modulus”
