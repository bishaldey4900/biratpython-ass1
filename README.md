#As a very beginner coder I have started my python journey with small calculator only.


#............Simple Calaculator.................

while True:
    print(" PLease select the operation that  you want to perform: ")
    print("1. Add")
    print("2. Sub")
    print("3. Mul")
    print("4. Div")
    print("5. Exit!!") 
    case = input("Enter your choice (1-5): ")
    if case == "5":
        print("Exiting the program  !!!!!.")
        break
    else:
        print("You have selected option", case, "Please enter the numbers to perform the operation: ")
        a = int(input("Enter the  1st number "))
        b = int(input("Enter the  2nd  number "))
        match case:      
            case "1":
                Result = (a + b) 
            case "2":
                Result = (a - b )     
            case "3":
                Result = (a * b) 
            case "4":
                Result = (a / b)      
        print ("Result: ", Result)
        


