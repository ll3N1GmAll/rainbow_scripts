# rainbow_scripts
Simple batch scripts to place in the root of your "rainbowcrack-1.6.1-win64" (or whatever version you have) folder to auto-create rainbow tables of almost any avialable type easily. Thus saving $2700 in the process!

This project contains several scripts. The script title details the hash algorithm, charset, min/max length, and the size of the resulting rainbow table. You will need at LEAST that much space to run the script. Simply double click on the script and let it run. It may run for hours, days, weeks, months, etc. depending on the table size and the hardware you are running it on.

These scripts are meant to simplify the process of rainbow table generation for pentesters who do not yet have the capital to invest in nearly $3000 to buy these tables outright. If you have the time to generate them this gives you a process that is "set it & forget it" and therefore reduces human error. 

Place each batch file (or whichever one you want for the table desired) into the root of your rainbowcrack applocation directory. Then run simply run the script and walk away.

Once the script is run, it will create all of the tables required. Then it will go through the sorting and processing operations; and finally create an appropriately named folder for the tables and move them into that folder for easy organization. Only one script/table can be run/generated at a time unless you want to have multiple copies of the rainbowcrack program. In this case a different script can be run in each folder to create multiple tables simultaneously; however, I highly doubt that would work properly as CPU is almost totally devoured by a single table generation process even on high powered i7 CPUs. 
