# List-Functions
lt=[]
x=int(input())
for i in range(x):
    s=input().split()
    if 'insert' in s:
        lt.insert(int(s[1]),int(s[2]))
    elif 'print' in s:
        print(lt)
    elif 'remove' in s:
       lt.remove(int(s[1]))
    elif 'append' in s:
        lt.append(int(s[1]))
    elif 'sort' in s:
        lt.sort()
    elif 'pop' in s:
        lt.pop()
    elif 'reverse' in s:
        lt.reverse()
        
