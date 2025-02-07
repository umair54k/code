print("hello marry")
print(1,2,3,4,5,6 ,sep=" ")

print(21+38 ,56-27, 87/4)
print("i am a software engineer \nand i am a good boy")
print("what are you doing")

a=4.3
b= 5+7
c= "umair"
print(a,b,c,sep=" ")
print("the type of a is", type (a))
print("the type of b is", type(b))
print("the type of c is", type(c))

a=89
b=54

print("the value of a+b is", a+b)
print("the value of a-b is", a-b)
print("the value of a/b is", a/b)
print("the value of a*b is", a*b)

colors= ["red","green","blue","yellow"]
for color in colors:
  print (color)
for i in colors:
  print (i)

name= ["amir" , "bilal" , "shaid", "haris" , "ali"]
for p in name:
  print (p)

car= ["cultus", "alto", "city", "vitz"]
for j in car:
  print (j)
------------------------------------------------------
marks=[4,6,8,"marry", "nancy"]
print(marks)

if "marry" in marks: 
 print("yes")
 
else:
     print("no")
if 8 in marks:
    print("hello")
    print (marks[:])
     
list=[i*i for i in range (10)]
print(list)
mist= [i*3 for i in range (20)
if i %3==0]
print(mist)
 ----------------------------------------------------------
l=[1,12, 92,46,4,6,8,20,20,10,10]
l.sort()
print(l)

l.sort(reverse=True)
print(l)

print(l.count(10))
m=l.copy()
m[0]=0
print(m)
m=[20,40,80]
k=(l+m)
print(k)
l.extend(m)
print(l)
 
------------------------------------------------------------------
countries=["pakistan","india","newyork,dubai"]
countries2=["nigeria","nepal","butan"]
southasia=countries+countries2
print(southasia)

tuple=(1,3,5,7,8,7,9,5,3,5,9)
res=len(tuple)
print('count of 9 in tuple:', res)
----------------------------------------------
letter="hey my name is {} ,\ni am from {} and \ni am {} years old"
name="marry"
country="pakistan"
age=30
print(letter.format (name,country,age))

price=49.9123
txt=f"for only {price:.3f} rupees!"
print(txt)
print(type (f"{2* 30}"))

----------------------------------------------------------------------------

st= input("enter a message") 
word= st.split(" ")
coding =input("1 for coding and 2 for decoding")
coding= True if (coding =="1") else False
print(coding)
if(coding):
  nwords =[] 
  for word in word:
    if(len(word)>=3):
      r1="spd"
      r2="ghj"
      stnew= r1 +word [1:]+ word[0] +r2
      nwords.append(stnew)
    else:
      nwords.appened(word[::-1])
    print(" " .join (nwords))
else:
  nwords= []


