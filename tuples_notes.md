
# 📘 Python Tuples – Complete Notes

## 🔹 1. What is a Tuple?
- A **tuple** is a collection which is **ordered** and **immutable**.
- Tuples are written using **parentheses `()`**.

---

## 🔹 2. Basic Properties
1. **Immutable** – Cannot change after creation  
2. **Ordered** – Elements retain order  
3. **Allows Duplicates** – Repeated values are allowed  
4. **Can store mixed data types** – Like int, float, string, list, etc.  
5. **Single element tuple requires a comma** – `(5,)` is a tuple; `(5)` is not  

---

## 🔹 3. Operations on Tuples
- Indexing (`t[0]`)
- Slicing (`t[1:3]`)
- Length: `len(t)`
- Membership: `in`, `not in`
- Concatenation: `t1 + t2`
- Repetition: `t * 2`
- Tuple unpacking: `a, b = (1, 2)`

---

## 🔹 4. Why Use Tuples?
- **Faster** than lists for read-only data
- **Safer** as data cannot be modified
- **Can be used as keys in dictionaries** (unlike lists)

---

## 🔹 5. Tuple vs List

| Feature         | Tuple       | List        |
|----------------|-------------|-------------|
| Mutable         | ❌ No        | ✅ Yes       |
| Syntax          | `(1, 2, 3)` | `[1, 2, 3]` |
| Performance     | Faster      | Slower      |
| Dictionary Key  | ✅ Allowed   | ❌ Not allowed |

---

