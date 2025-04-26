# 📖 Python Complete Basics — With Examples

```python
# 📌 PRINT: Python'da ekrana yazı yazdırmak için kullanılır.
print("Hello, World!")  # Ekranda 'Hello, World!' yazdırır

# 📌 VARIABLES: Değişkenler, verileri depolamak için kullanılır.
name = "Alex"           # String (metin)
age = 25                # Integer (tam sayı)
height = 1.70           # Float (ondalıklı sayı)
is_student = True       # Boolean (True/False)

# 📌 DATA TYPES: Python'da veri tipleri vardır.
print(type(name))       # str
print(type(age))        # int
print(type(height))     # float
print(type(is_student)) # bool

# 📌 USER INPUT: Kullanıcıdan veri almak için input() fonksiyonu kullanılır.
user_name = input("Enter your name: ")
print("Hi " + user_name)

# 📌 MATH OPERATIONS: Matematiksel işlemler için kullanılan operatörler.
x = 10
y = 3
print(x + y)   # 13
print(x - y)   # 7
print(x * y)   # 30
print(x / y)   # 3.333
print(x % y)   # 1
print(x ** y)  # 1000 (üs alma)

# 📌 STRING METHODS: String (metin) üzerinde işlem yapmak için kullanılır.
text = "Python"
print(len(text))    # 6
print(text.upper()) # PYTHON
print(text.lower()) # python
print(text[0])      # P
print(text[2:5])    # tho

# 📌 IF ELSE: Koşul ifadeleri ile karar yapıları kurulur.
age = 18
if age >= 18:
    print("You are an adult")
else:
    print("You are not an adult")

# 📌 LOGICAL OPERATORS: Mantıksal işlemler için kullanılır.
a = True
b = False
print(a and b)  # False
print(a or b)   # True
print(not a)    # False

# 📌 FOR LOOP: Döngüler, belirli bir kodu birden fazla kez çalıştırmak için kullanılır.
for i in range(5):
    print(i)  # 0 1 2 3 4

# 📌 WHILE LOOP: Koşul sağlandığı sürece kodu çalıştırmak için kullanılır.
count = 0
while count < 3:
    print("Count is", count)
    count += 1  # Count'u artırır

# 📌 LISTS: Listeler birden çok öğeyi saklamak için kullanılır.
fruits = ["apple", "banana", "cherry"]
print(fruits[0])   # apple
fruits.append("orange")   # yeni öğe ekler
fruits.remove("banana")   # öğe çıkarır
print(fruits)

# 📌 TUPLES: Değiştirilemeyen veri türüdür.
person = ("Alex", 25, "USA")
print(person[0])  # Alex

# 📌 DICTIONARIES: Anahtar-değer çiftleriyle veri saklar.
student = {
    "name": "Alex",
    "age": 25,
    "country": "USA"
}
print(student["name"])  # Alex
student["age"] = 26     # Değeri günceller

# 📌 FUNCTIONS: Fonksiyonlar, belirli bir işlevi birden fazla kez kullanmak için yazılır.
def greet(name):
    print("Hello " + name)

greet("Alex")  # Hello Alex

# 📌 FUNCTION WITH RETURN: Fonksiyonlar bir değer döndürebilir.
def add(a, b):
    return a + b

result = add(5, 7)
print(result)  # 12

# 📌 FILE OPERATIONS: Dosya okuma ve yazma işlemleri.
file = open("example.txt", "w")
file.write("Hello File!")
file.close()

file = open("example.txt", "r")
content = file.read()
print(content)  # Hello File!
file.close()

# 📌 TRY EXCEPT: Hata yakalama için kullanılır.
try:
    num = int(input("Enter a number: "))
    print(num)
except:
    print("Invalid input")

# 📌 CLASSES AND OBJECTS: Nesne yönelimli programlamada kullanılan yapılar.
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def say_hi(self):
        print("Hi, I'm " + self.name)

p1 = Person("Alex", 25)
p1.say_hi()  # Hi, I'm Alex

# 📌 IMPORT MODULE: Python'da dış kütüphaneleri kullanmak için import edilir.
import math
print(math.sqrt(16))  # 4.0

# 📌 COMMENTS: Kodu açıklamak için kullanılır.
# Bu bir tek satırlık yorumdur

"""
Bu ise
çok satırlı
bir yorumdur
"""
