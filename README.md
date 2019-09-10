# datediff
a shell script to calculate date differences in different time units.

requirements:
bash, bc

usage:
datediff -s|--start-date <date format> [-e|--end-date <date format>] [-t|--time-unit <time unit>] 

<date format>: 
\"YYYY-MM-DD [HH24:MI:SS]\"

<time unit>:  
[human-readable | seconds | minutes | hours | days]
    default:  human-readable

end date: default: now ($now)

example: datediff -s \"2019-09-10 14:25:14\" -e \"2019-09-10 14:40:00\"" -t seconds
