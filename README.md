# btcdice
This script will use the cryptographic toolset usually included out of the box on most unix/Linux distributions to generate a bitcoin wallet. You will need 16 sided dice to generate the entropy for this script, the dice can be hexadecimal dice (0-F) or they can be 16 sided dice using regular numbers (1-16). 

I use this to generate my own offline wallets for cold storage, but if you are unable to verify the code yourself to your satisfaction you shouldn't use it, there are other ways to generate bitcoin addresses from dice with peer reviewed code.

## usage   
`source makeaddress.sh`    
`newAddress 0x<roll the dice 64 times and put results here>`   
## If using 16 sided dice without HEX notation   
If your dice only has 'numbers' and no letters you need to convert the two-digit numbers into hexadecimal notation.   
Replace two-digit numbers as follows:   
10 = A   
11 = B   
12 = C   
13 = D   
14 = E   
15 = F   
16 = 0   
   
