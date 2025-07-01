### calculate the sum of first n natural numbers using a while loop and for loop

n=10
sum=0
# Using a while loop
count = 1
while count <= n:
    sum += count
    count += 1
print("Sum of first", n, "natural numbers using while loop is:", sum)


Output : Sum of first 10 natural numbers using while loop is: 55

# Using a for loop
n=10
sum=0

for i in range(11):
    sum += i
print("Sum of first", n, "natural numbers using for loop is:", sum)

output: Sum of first 10 natural numbers using for loop is: 55

# Prime number between 1 to 100
for num in range(1,101):
    if num>1:
        for i in range(2,num):
            if num%i==0:
                break
        else:
            print(num, "is a prime number")

Output:
2 is a prime number
3 is a prime number
5 is a prime number
7 is a prime number
11 is a prime number
13 is a prime number
17 is a prime number
19 is a prime number
23 is a prime number
29 is a prime number
31 is a prime number
37 is a prime number
41 is a prime number
43 is a prime number
47 is a prime number
53 is a prime number
59 is a prime number
61 is a prime number
67 is a prime number
71 is a prime number
73 is a prime number
79 is a prime number
83 is a prime number
89 is a prime number
97 is a prime number
