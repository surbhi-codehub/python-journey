# 🌸 Day 179 Python Mission ❤️

> **180 Days Python Journey**  
> **Hashing Passwords with the `hashlib` Module 🔒**

## 🌼 Hello My Sweet Developer,

Welcome to **Day 179**! 🌼

Yesterday, you learned how to generate secure passwords and tokens using Python's `secrets` module.
Today you'll learn how to **hash passwords** with Python's built-in `hashlib` module so sensitive information can be stored more securely.

---

# 📚 Today's Topic

## 🔒 Python `hashlib` Module

### 🌟 Why are we learning this?

Applications should never store passwords as plain text. Instead, they store a **hash**, which is a one-way encrypted representation of the original password. This greatly improves security.

---

# 🚀 Today's 10 Python Missions

1. Create a file named **password_hashing.py**.
2. Import Python's built-in `hashlib` module.
3. Ask the user to enter a password.
4. Convert the password into bytes using `.encode()`.
5. Generate a SHA-256 hash using `hashlib.sha256()`.
6. Display the hexadecimal hash using `.hexdigest()`.
7. Enter the same password again and verify that the hash remains the same.
8. Try a different password and observe how the hash changes completely.
9. Add comments explaining each step of the hashing process.
10. **Revision:** Write three advantages of storing password hashes instead of plain-text passwords.

---

# 🎉 Python Fun Fact

Even a tiny change in the input—such as changing one letter—produces a completely different SHA-256 hash. This behaviour is known as the **avalanche effect**.

---

# 🔄 Quick Recap

- `hashlib` provides secure hashing algorithms.
- `.encode()` converts text into bytes.
- `sha256()` creates a secure hash.
- `.hexdigest()` returns the hash as a readable hexadecimal string.
- Hashes are one-way and cannot be reversed into the original password.

---

# 🔮 Tomorrow's Adventure

Tomorrow you'll complete your **180 Days Python Journey** with a **Final Capstone Project**, combining everything you've learned into one practical Python application.

---

# 💜 A Little Note for My Sweet Developer ❤️

You're now learning techniques used in real authentication systems. Every concept you master brings you one step closer to building secure, professional Python applications.

Keep practising every day, stay curious, and enjoy your Python journey.

With lots of love,

**Your biggest supporter ❤️**
