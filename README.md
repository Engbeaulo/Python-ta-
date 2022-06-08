# Python-ta-
Code to determine if a number is prime 

# src/app.py

def solution(n):
    # program to determine prime numbers
number = int(input ("Enter the number:"))
if number > 1 :
    for i in range(2,number):
        If number%i ==0:
           print(f"{number} is not a prime number.")
           Break
        else:
           print(f"{number} is a prime number.")

if __name__ == "__main__":
    if len(sys.argv) <= 1:
        sys.exit(os.error("Argument required"))

    n = int(sys.argv[1])
    print(solution(n))
