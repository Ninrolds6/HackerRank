# Question 1 (Say "Hello World!" with Python)

print("Hello, World!")

# Question 2 (Python If-else)

n = int(input().strip())
if n%2!=0:
    print("Weird")
elif n%2==0 and (n > 2 and n <= 6):
    print("Not Weird")
elif n%2==0 and (n > 6 and n <= 20): 
    print("Weird")
else:
    print("Not Weird")

# Question 3 (Arithmetic Operators)

a = int(input())
b = int(input())
while (a <= (10**10)) and (a >= 1):
    if (b <= (10**10)) and (b >=1):
        sum_ = a + b
        difference = a - b
        product = a * b
        print (sum_)
        print (difference)
        print (product)
        break
        
# Question 4 (Python : Division)

a = int(input())
    b = int(input())
    print(a//b)
    print(a/b)

# Question 5 (Loops)

if __name__ == '__main__':
    n = int(input())
for i in range(n):
    print (pow(i,2))

# Question 6 (Write a Function)

def is_leap(year):
    leap = False
    if ((year % 4 == 0) and (year % 100 != 0)):
        leap = True
    elif (year % 400 == 0):
        leap = True
    else:
        leap = False
    
    return leap
    
 # Question 7 (Print Function)
 
 n = int(input())
for i in range(1,n + 1):
    print(i, end='')
    
# Question 8 (List Comprehension)

x = int(input())
    y = int(input())
    z = int(input())
    n = int(input())
l=[x for x in range(x+1)]
m=[y for y in range(y+1)]
p=[z for z in range(z+1)]
o=[[x,y,z]for x in l for y in m for z in p if x+y+z!=n]
print(o)

Question 9 (Nested List)

if __name__ == '__main__':
    li = [] 
    s = []
    for _ in range(int(input())):
        name = input()
        score = float(input())
        s.append(score)
        li.append([name, score])
    li.sort(key=lambda x: x[1])
    lst = [] 
    s = set(s)  
    num = sorted(s)[1]
    for i in range(0,len(li)):
        if float(li[i][1]) == num:
            lst.append(li[i][0])
    lst.sort()
    print(*lst,sep='\n')
    
    
