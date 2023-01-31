# Basic-Calculator
you can use this code for doing some basic calculcation as like (Addition,Subtraction,Multiplication,Devition,Exponential,Modulus)



    print("********** Welcome to basic calculator **********")
    print("\n")

    Num_1= float(input("Please enter your 1st number: "))
    Num_2= float(input("Please enter your 2nd number: "))

    print("Enter 1 for 'Addition'\nEnter 2 for'Subtraction'\nEnter 3 for 'Multiplication'\nEnter 4 for 'Devition'\nEnter 5 for 'Exponential'\nEnter 6 for 'Modulus' ")
    Entered_number=int(input("Please chose your number 1 to 6: "))

    if Entered_number == 1:
        print("The sumation of your number : ",Num_1 + Num_2)
    elif Entered_number == 2:
        print("The subtraction of your number : ",Num_1 - Num_2)
    elif Entered_number == 3:
        print("The Multiplication of your number : ",Num_1 * Num_2)
    elif Entered_number == 4:
        print("The Devition of your number : ",Num_1 / Num_2)
    elif Entered_number == 5:
        print("The Exponetial of your number : ",Num_1 ** Num_2)
    elif Entered_number == 6:
        print("The Modulus of your number : ",Num_1 % Num_2)
    else:
        print("Your chose number is invalid,Please tray agin,\n\n********** Thank you **********")
 
 
 
Thank you
