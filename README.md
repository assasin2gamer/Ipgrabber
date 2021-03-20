# Ipanalysis
Grabs first ip of a line (for log analysis)
It scans through a txt file and finds each unique ip adress and counts duplicates.

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
