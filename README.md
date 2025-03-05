Key Features
🔹 Password Strength Analysis
The tool evaluates password security based on:
✔ Length Check – Passwords must be at least 8 characters long.
✔ Common Passwords Check – Compares against a list of commonly used passwords to prevent weak selections.
✔ Repetition Detection – Detects repeated sequences of characters to prevent predictable patterns.
✔ Special Character Requirement – Ensures the inclusion of symbols like @, #, $, % to enhance security.

🔹 Secure Password Storage with Encryption
Passwords are stored securely in an encrypted format to protect sensitive data. The encryption ensures that even if the storage file is accessed, the actual passwords remain hidden.

✔ AES-based Encryption – Uses cryptography.fernet to encrypt and decrypt passwords.
✔ Automatic Encryption Key Handling – Generates a secret key (key.key) that is used for encrypting and decrypting passwords.
✔ Structured Storage – Saves passwords in a JSON file (passwords.json), associating each password with a website.

🔹 Easy Password Retrieval
Users can retrieve their stored passwords by providing the associated website name. The tool decrypts and displays the password securely.

✔ Quick Lookup – Retrieves passwords in seconds.
✔ Decryption on Demand – The password remains encrypted in storage and is only decrypted when accessed
