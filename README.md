# py4e-Autograder-Exercise-8.5-py-file
Autograder: Exercise 8.5-solution 


We have to check two conditions here. 
If you look into the "mbox-short.txt " file, you can find the single mailId is repeated twice as "From bla bla bla" & "from: bla bl bla..."
As mentioned in the question we should go for two conditional chexk to avaoid the redundancy.
initially i got the count value of 54. I corrected later to get "Done".


///////	if not line.startswith('From'):continue///////
/////	if not line.startswith('From:'):continue/////
	
