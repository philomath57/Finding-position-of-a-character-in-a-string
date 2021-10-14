# Finding-position-of-a-character-in-a-string
Function has been created with the help of which the position of a particular character in a string can be determined and shown in a list
def findall(str1):
  str2='Faiyaz'
  l=[]
  for i in range (len(str2)):
    if str2[i] == str1:
      l.append(i)
  print(l)
findall('a')
