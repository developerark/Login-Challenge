# Login-Challenge
Programming Challenge for my Python Students

Documentation:
	This document describes public functions in module ark.

	Usage:
		Download ark.pyc in the folder you have your main program on.
		Import the module to your main program using the import keyword
		Eg:
			import ark

	Public Functions:
		1)	def login(tUsername, tPassword):
				Description:
					This function returns a string "Access Granted" 
					if both the username and password passed to it is correct
				Arguments:
					tUsername := test username to the function
					tPassword := test password to the function
				Returns:
					Returns the string "Access Granted" if 
					username and password are both correct
					Returns the string "Access Denied" if 
					either of the arguments are incorrect
				Usage:
					import ark
					ark.login('cat', 'mew')	# Should Return the string "Access Denied"

	Challenge:
		To make this task a little easier I am giving you the username of one of the user. 
		The user name is "root", without quotes. 
		The challange here is to guess this user's password. 
		You can assume the password is of length 3 and each letters in the password can be 
		either lowercase character or uppercase character (no numbers or special characters)

