# bingo
# sample1

import random
from random import sample

k=sample(range(1,76),75)
n=[]

for i in range(75):
   x=input("next number(Enterキー)")
   n.append(k[i])
   x=n[i]
   print(i+1,"回目:","\033[1m{}\033".format(x))
   print("記録：",n)
