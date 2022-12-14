# Get-code-...
#Write a program to guess the number,and if it not guess then game over...
while (1):
    i = int(input("Enter a number : "))
    if (i>=2) and (i<=4):
        print("tum abhi door ho.")
        continue

    elif (i>=4) and (i<=6):
        print("tum abhi bhi door ho.")
        continue
    elif (i>=6) and (i<=8):
        print("tum abhi thoda nazdeek ho.")
        continue
    elif (i>=8) and (i<=10):
        print("congrates ,Tum pohoch gaye ho.")
        break
    else:
        print("Game Over.")
        break
