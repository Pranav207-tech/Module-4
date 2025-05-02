# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values
## Name: Pranav k
## Reg no: 212224040240
This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
def dictionairy():     
key_value ={}    
key_value[2] = 56       
key_value[1] = 2 
key_value[5] = 12 
key_value[4] = 24 
key_value[6] = 18      
key_value[3] = 323 
print ("Keys and Values sorted","in alphabetical order by the value") 
print(sorted(key_value.items(), key = lambda kv:(kv[1], kv[0])))
```

## Output
![image](https://github.com/user-attachments/assets/ea7855ed-fe54-4d5d-ae34-11062eb64abd)

## Result
Thus,the program has been executed successfully.
