# Candy Bianca Package (model BWD 596PH3/5-S)
Froked from: https://github.com/wariat85/hm_candy_bianca

This is my personal package of Candy Bianca Integration and works with BWD 596PH3/5-S model.

Below the list of functionality:
 - Get status of washing --> Tested & Works
 - Get the program --> Tested & Works
 - Get the rem time --> Tested & Works
 - Get the temperature --> Tested & Works
 - Get the spin speed --> Tested & Works
 - Send STOP Washing COMMAND --> Tested & Works
 - Send RUN Washing COMMAND --> Tested & Works

I have set only 4-5 washing program, the others can be retrieved "sniffing" the network traffic of own smartphone.

16/08/2024
- Removed unsed automation
- Removed code not compatible with new Home Assistant version (2024.8.1)
- Cleaned up code
- Added online sensor

TO DO
Fix IP in Rest commmand to use the ip set in input and not in yaml file
