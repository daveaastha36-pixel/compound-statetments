***conditional statement examples***

---

## 1. Student Biology Marks (if-else)

```python
biology_marks = int(input("Enter Biology Marks: "))

if biology_marks >= 90:
    print("Grade: A+")
elif biology_marks >= 75:
    print("Grade: A")
elif biology_marks >= 50:
    print("Grade: B")
else:
    print("Fail")
```

---

## 2. NEET Marks (if-else)

```python
neet_marks = int(input("Enter NEET Marks: "))

if neet_marks >= 650:
    print("Excellent Chance")
elif neet_marks >= 550:
    print("Good Chance")
elif neet_marks >= 450:
    print("Average Chance")
else:
    print("Needs Improvement")
```

---

## 3. Medical Shop Permission (while + if-else)

```python
while True:
    area = int(input("Enter Medical Shop Area (sq.ft): "))

    if area >= 300:
        print("Permission Approved")
    else:
        print("Permission Rejected")

    choice = input("Check another shop? (yes/no): ")

    if choice.lower() == "no":
        break
```

---

## 4. Bones Calculation (Function)

```python
def bones_count(age):
    if age < 18:
        print("Approximately 270 bones")
    else:
        print("Approximately 206 bones")

age = int(input("Enter Age: "))
bones_count(age)
```

---

## 5. Hospital Bill Calculation

```python
bill = float(input("Enter Hospital Bill: "))

if bill >= 50000:
    discount = bill * 0.10
elif bill >= 20000:
    discount = bill * 0.05
else:
    discount = 0

final_bill = bill - discount

print("Discount:", discount)
print("Final Bill:", final_bill)
```

---

## 6. Laboratory HDL and LDL Report

```python
hdl = int(input("Enter HDL Value: "))
ldl = int(input("Enter LDL Value: "))

if hdl >= 60:
    print("HDL: Healthy")
else:
    print("HDL: Low")

if ldl < 100:
    print("LDL: Normal")
elif ldl <= 129:
    print("LDL: Near Optimal")
else:
    print("LDL: High")
```

---

## 7. Living Species (Animal or Bird)

```python
species = input("Enter Species (animal/bird): ")

if species.lower() == "animal":
    print("Animals usually have four legs.")
elif species.lower() == "bird":
    print("Birds have wings and feathers.")
else:
    print("Unknown Species")
```

---

## 8. Land Square Feet Calculation

```python
length = float(input("Enter Length: "))
width = float(input("Enter Width: "))

area = length * width

print("Area:", area, "sq.ft")

if area >= 1000:
    print("Large Land")
else:
    print("Small Land")
```

---

## 9. Microscope Range

```python
magnification = int(input("Enter Microscope Magnification: "))

if magnification <= 40:
    print("Low Power")
elif magnification <= 400:
    print("Medium Power")
else:
    print("High Power")
```

---

## 10. Medical Equipment Price Calculation

```python
product = input("Enter Product Name: ")
quantity = int(input("Enter Quantity: "))
price = float(input("Enter Price Per Product: "))

total = quantity * price

if total >= 100000:
    discount = total * 0.15
elif total >= 50000:
    discount = total * 0.10
else:
    discount = 0

final_amount = total - discount

print("Product:", product)
print("Total Amount:", total)
print("Discount:", discount)
print("Final Amount:", final_amount)
```

---





