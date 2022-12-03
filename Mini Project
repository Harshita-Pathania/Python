def Intro():
    print("***********************************WELCOME***********************************")
    print("***Python Mini Project: To convert Roman numerals to decimal number system***")
    print("Name: Harshita Pathania")
    print("Registration No.: 1221XXXX")
    print("Section: K22XX")
    print("Roll no.: 17")

def roman(a):
    if(a == 'I'):
        return 1;
    elif(a == 'V'):
        return 5;
    elif(a == 'X'):
        return 10;
    elif(a == 'L'):
        return 50;
    elif(a == 'C'):
        return 100;
    elif(a == 'D'):
        return 500;
    elif(a == 'M'):
        return 1000;

def con(str):
    s=0
    i=0
    while (i<len(str)):
        s1=roman(str[i])
        if (i+1<len(str)):
            s2=roman(str[i+1])
            if (s1>=s2):
                s=s+s1
                i=i+1
            else:
                s=s+s2-s1
                i=i+2
        else:
            s=s+s1
            i=i+1 
    print(s)
    x=int(input("Enter 1 to continue and 2 to exit:\n"))
    cont(x)


def cont(x):
    if x == 1:
        print("Enter Roman Numeral")
        b=str(input())
        con(b)

    elif x == 2:
        print("**********Thank You**********")
    else:
        print("***Invalid Input***")
        x=int(input("Enter 1 to continue and 2 to exit: \n "))
        cont(x)


Intro()
x=int(input("Enter 1 to continue and 2 to exit:\n"))
cont(x)
