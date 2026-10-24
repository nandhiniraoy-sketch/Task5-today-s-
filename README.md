# Task 5: Python Lists, Tuples, Sets and Dictionaries

## Objective
Learn Python collection data structures and perform operations such as adding, removing, searching, and updating elements.

---

# 1. List

## Program
```python
fruits = ["Apple", "Banana", "Mango"]
print(fruits)

fruits.append("Orange")
fruits.insert(1, "Grapes")
fruits.remove("Banana")
fruits.pop(0)

print(fruits)
print("Mango" in fruits)

numbers = [5, 2, 8, 1]
numbers.sort()
print(numbers)
```

---

# 2. Tuple

## Program
```python
colors = ("Red", "Blue", "Green")

print(colors)
print(colors[1])

numbers = (1, 2, 2, 3, 2)
print(numbers.count(2))
print(colors.index("Green"))
```

---

# 3. Set

## Program
```python
numbers = {1, 2, 3, 3, 4}

print(numbers)

numbers.add(5)
numbers.remove(2)

print(numbers)
print(3 in numbers)
```

---

# 4. Dictionary

## Program
```python
student = {
    "Name": "Rahul",
    "Age": 20,
    "Branch": "CSE"
}

print(student)

print(student["Name"])

student["College"] = "Vignan"
student["Age"] = 21

student.pop("Branch")

print(student)
print("Age" in student)
```

---

# Comparison Table

| Feature | List | Tuple | Set | Dictionary |
|---------|------|-------|-----|------------|
| Ordered | Yes | Yes | No | Yes |
| Changeable | Yes | No | Yes | Yes |
| Duplicates | Yes | Yes | No | Keys: No |
| Symbol | [] | () | {} | {key:value} |

---

# Conclusion

This task demonstrates Python Lists, Tuples, Sets, and Dictionaries. It includes basic operations like adding, removing, searching, updating, and comparing the four collection data structures.# Task5-today-s-
