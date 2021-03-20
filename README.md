# Ipanalysis
Grabs first ip of a line (for log analysis)
It scans through a txt file and finds each unique ip adress and counts duplicates.

Second box is to remove the first characters of the log for each line. It MUST find the ip adress as the FIRST THING. So count the character count (including spaces) and input it to remove stuff like dates and other stuff. 

For example: 

213.2.2.2 //3/9/21/ ---> 112.4.2.1 Get package
213.2.2.2 //3/9/21/ ---> 112.4.2.1 Get package
213.2.2.2 //3/9/21/ ---> 244.4.2.1 Get package
216.2.2.2 //3/9/21/ ---> 112.4.2.1 Get package

Would result in:

213.2.2.2
216.2.2.2

213.2.2.2 came up 3 time.
216.2.2.2 came up 1 time.

Email: Yougohomemonster@gmail.com
