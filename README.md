# ing2gnucashIM
ING to GNU Cash IMproved



## What
This python script converts a Dutch ING, consumer market, semicolon delimited .CSV (Puntcomma gescheiden .CSV) account export file, to something that can be used to import into GNU Cash.

## How
Syntax: `ing2gnucashim [-h] filename`

Where filename is the exported .CSV file. 
-h shows the help message.

Output writes to the command line, so an extra step needs to be taken to make a newly formatted .CSV file:
`ing2gnucashim original.csv > new.csv`

Use the outputfile to import into GNU Cash, or any other accounting software that needs the debit and credit values to be seperated. (Something ING just doesn't do for the ordinary consumer proletariat)

## Who
I'm not a sofware engineer and this is my first public published script. But only because I ripped it from someone else. I'm a git n00b, but please feel free to jump in and make your own modifications.


## Credits:
This script has been shamelessly plagiarized by me from the presumably unlicensed source: https://github.com/hjmeijer/ing2gnucash

I've modified it to work with python3, added a first line with field description and added the account en contra_account fields.

## Update
