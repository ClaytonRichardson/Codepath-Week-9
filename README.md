# Codepath-Week-9
Time Spent: **30+** hours spent in total

## Honey pots used

The only honeypot that I used was dionaea.

## Issues Encountered

I encountered several issues while setting up the MHN admin application. Some how the process ended
early and printed out an error message to run a certain command. After running the specified command,
a new error would appear prompting me I do not have permission to run the command. So I put the directory
in root, and I tried to re run the command, it still did not work because it was asking for a password
that I had no knowledge of. I had to restart the entire process of this, and it finally worked on the 3rd
attempt. The other issues I faced has to deal with exporting the data. I would run the commands given to us
on the GCP platform and the shell told me that those were invalid commands. --db and --connection were not
able to be used by my shell. After plenty of research I found no way of exporting the session.json data file, 
I could view all the contents of the file in the admin vm however. 

## Summary of Results

Dionaea had a total of 8374 attacks

![Alt Text](https:github.com/ClaytonRichardson/Codepath-Week-9/blob/master/SummaryOfAttacks.PNG)
