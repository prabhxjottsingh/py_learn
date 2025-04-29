## 🆚 Tuple vs List in Python

### ✅ Key Differences

| Feature     | List                     | Tuple                         |
| ----------- | ------------------------ | ----------------------------- |
| Syntax      | `[1, 2, 3]`              | `(1, 2, 3)`                   |
| Mutability  | Mutable (can be changed) | Immutable (cannot be changed) |
| Methods     | Many built-in methods    | Fewer built-in methods        |
| Performance | Slower than tuples       | Faster than lists             |
| Use Cases   | Dynamic data             | Fixed data                    |

---

### 🧪 Python Example

```python
# List Example
my_list = [1, 2, 3]
my_list.append(4)
print("List:", my_list)  # Output: List: [1, 2, 3, 4]

# Tuple Example
my_tuple = (1, 2, 3)
# my_tuple.append(4)  # ❌ This will raise an AttributeError
print("Tuple:", my_tuple)  # Output: Tuple: (1, 2, 3)
```

---

### 📝 Summary

- Use **lists** when your data needs to change (add, remove, update).
- Use **tuples** when your data should stay constant and for better performance.
