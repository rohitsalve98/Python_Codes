.. code:: ipython3

    import random
    a=random.randint(0,6)
    while True:
        b=int(input("Please enter number to match"))
        if (a==b):
            print("GAME OVER")
        elif (a>b):
            print("enter greater number")
        elif (a<b):
            print("enter lesser number")
                                        

:

    Please enter number to match1
    GAME OVER
    Please enter number to match2
    enter lesser number
    Please enter number to match3
    enter lesser number
    Please enter number to match4
    enter lesser number
    Please enter number to match5
    enter lesser number
    Please enter number to match6
    enter lesser number
    Please enter number to match7
    enter lesser number
    Please enter number to match1
    GAME OVER
    

