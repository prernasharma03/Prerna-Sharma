#  Competitive Progamming

# 1st Year

## Task 1

## SPOT THE ERROR

### Question 1
Question 1:

K = [3,1,9,'b','a'      
for i in K:       
&nbsp; &nbsp; &nbsp; if i==a         
      &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   break:                  
&nbsp; &nbsp; &nbsp; else:       
print("A")


#### Answer 1
K = [3,1,9,'b','a']   &nbsp;&nbsp;  # "]" was missing   
for i in K:   
 &nbsp;&nbsp;&nbsp; if i=='a': &nbsp; #a is a character and also added ":" at the end   
          &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   break  &nbsp; &nbsp; #removed ":"         
&nbsp;&nbsp;&nbsp; else:    
          &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print("A") &nbsp; &nbsp;  #indented

### Question 2

K=int(input("Enter a number:"))  
L = 0   
for j in range(1,K,2)   
l += 1   
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; if j%2=0:  
  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print("Code Chef" * 2)  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; else:  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print("Code Chef" * 3)  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print[L]

#### Answer 2
K=int(input("Enter a number: "))   
L = 0   
for j in range(1,K,2): &nbsp; &nbsp; #added ":" at the end   
 &nbsp; &nbsp; &nbsp;  L += 1  &nbsp;  # replaced "l" with "L" and indentation required   
&nbsp; &nbsp; &nbsp;   if j%2==0: &nbsp; # comparison operator "==" instead of assignment operator "="   
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print("Code Chef " * 2) &nbsp; #indented     
&nbsp; &nbsp; &nbsp;  else:    
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print("Code Chef " * 3) &nbsp; #indented    
print(L) &nbsp; #no indentation required and replaced "[]" with "()"

### Question 3

def extendList(val; list==[])    
list.append(val)          
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; return list   
list1 = ExtendList(10)    
list2 = extendList(123,[])    
list3 += extendList('a) 

print ["list1 =", list1]     
printf("list2 =", list2)       
print ["list3 =", list3}        

#### Answer 3
def extendList(val, list=[]):  #replaced comparison operator "==" with assignment operator "=" and also ";" with ","     
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  list.append(val)  #indented  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; return list   
list1 = extendList(10) &nbsp; #replaced "E" with "e" in the function extend()    
list2 = extendList(123,[])     
list3 = extendList('a') &nbsp; #list3 is uninitialized so removed "+" from "+=" and also added closing " ' " after a  
print ("list1 =", list1) &nbsp; # replaced "[]" to "()"   
print("list2 =", list2) &nbsp; #"printf" to "print"   
print("list3 =", list3) &nbsp; #replaced "[" with "(" and "}" with ")"    

### Question 4

def compound_interest(principle, rate, time)   
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; principle,rate,time=0,0,0   
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Amount = principle * ( ((1 + rate / 100) * time))    
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; CI = Amount - principal    
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print("Compound interest is", Ci) 


p = float(input(“enter the principle”))     
r = float(input(“enter the principle”)     
t = float(input(“enter the principle’))

compound_interest(p; r)

#### Answer 4

def compound_interest(principal, rate, time): &nbsp; added ":" at the end and changed "principle" to "principal everywhere"     
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  #removed the second unnecessary line     
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Amount = principal * ( ((1 + rate / 100) ** time))   #replaced multiplication operator * by exponentiation operator **    
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; CI = Amount - principal    
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; print("Compound interest is", Ci)  &nbsp; #capital "I" in CI

p = float(input("enter the principal ")) &nbsp; #"principle" to "principal"     
r = float(input("enter the rate ")) &nbsp;  "principle" to "rate"     
t = float(input("enter the time "))  &nbsp; # replaced "principle" to "time"     
compound_interest(p, r, t) &nbsp; #added argument t and also replaced ";" by ","

# Task 2
## MCQ
### 1
c
### 2
d
### 3
d
### 4
a
### 5
d
### 6
b
### 7
b
### 8
c
### 9
c  
### 10                             
a
