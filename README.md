# dolgs
dolgs volkov
# Язык Phyton
## 1 задание 
[Uploaprint(float(input()) + float(input()))
ding volkov1.py…]()
## 34 задание 
[Uploading волков 34.py…]()
## действие в 1 задании
print(float(input()) + float(input()))
## действие в 34 задание 
import random

I = input("камень, ножницы, бумага? ").lower()
Bot = random.choice(["камень", "ножницы", "бумага"])
print(f"Вы: {I}, Бот: {Bot}")

if I == Bot: print("Ничья!")
elif (I == "камень" and Bot == "ножницы") or \
     (I == "ножницы" and Bot == "бумага") or \
     (I == "бумага" and Bot == "камень"): 
 print("Выиграл!")
else:
 print("Проиграл!") 
 print("повезет в следуюший раз!")





 
