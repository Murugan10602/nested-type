# nested-type
#nested if statement in python:
"""
 3 marks Input 
 total 
 average 
 result 
 if pass grade
 90-100  grade a
 80-89   grade b
 70-79   grade c

 """
e=int(input("how many students:"))
while e>=1:
  name=input("your name:")
  m1=int(input("mark1:"))
  m2=int(input("mark2:"))
  m3=int(input("mark3:"))
  Total=m1+m2+m3
  avg=Total/3.0

  if m1>=35 and m2>=35 and m3>34:
    print("result: pass")
    if avg>=90 and avg>101:
      print("very good: Grade a")
    elif avg>=80 and avg>90:
      print("good: Grade b")
    elif avg>=70 and avg>80:
      print(" keep try: Grade c")
    elif avg<70:
      print("Grade d")

  else:
    print("Result: fail")
    print("no grade")
