# Day 03 – Linux Permissions & Python if-else 🚀

Today I focused on Linux permissions and Python conditional statements with hands-on practice.

---

# Linux Learning 🐧

## Topics Covered

### Linux Permissions

Permission values:

```text
r = Read = 4
w = Write = 2
x = Execute = 1
```

Examples:

```text
755 = rwxr-xr-x
644 = rw-r--r--
600 = rw-------
640 = rw-r-----
750 = rwxr-x---
```

---

## Commands Practiced

### View permissions

```bash
ls -l
```

Purpose:

```text
Display file permissions and ownership
```

---

### Change permissions

```bash
chmod 755 script.sh
chmod +x deploy.sh
chmod 640 api.key
chmod 750 app/
```

Purpose:

```text
Modify access permissions
```

---

### Change ownership

```bash
sudo chown ubuntu:developers app/
sudo chown -R jenkins:devops project/
sudo chown devops:cloud api.key
```

Purpose:

```text
Change file and folder ownership
```

---

# Python Learning 🐍

## Revision

Topics revised:

* Variables
* Data Types
* Type Conversion
* Comparison Operators

```python
name = "DevOps"
age = 22
height = 5.8
is_student = True

print(type(name))
print(type(age))
```

---

## if-else Basics

Example:

```python
age = 17

if age >= 18:
    print("Eligible")

else:
    print("Not Eligible")
```

Output:

```text
Not Eligible
```

---

## Skills Learned Today

✅ Linux file permissions
✅ Ownership management
✅ chmod and chown
✅ Recursive ownership (-R)
✅ Variables and data types
✅ Comparison operators
✅ Basic if-else conditions

---

## Learning Summary

Small progress every day builds stronger skills over time.
