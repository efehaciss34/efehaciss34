import random 
 
şifre=int(input("şifreniz:"))


while true:
tahminler=random.randint(0,10000)
print(tahminler)

if tahminler==şifre:
break
print("şifre kırıldı")
