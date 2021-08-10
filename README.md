# vehicle_registration_number_generator
this project generates a registration number for vehicle based on area of residence in chennai 
the registration number has three parts 
the first part is the state (TN for tamilnadu) and then followed by two numbers
these numbers indicate the area of residence starting from 00 to 99
the numbers from 01 to 14 are within chennai
an if else ladder is used to create the first part of the number based on user's choice
the second part is a two digit alphabet which is in upper case
the random function is used and the floor function from the math library are used for this operation (26 characters)
the third part is a four digit number
the random function is used and the floor function from the math library are used for this operation (10 characters)
combining all these three we obtain the vehicle registration number
