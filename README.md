# Sparrow Documentation

![MicroIntel Logo](https://raw.githubusercontent.com/microintel/endgram/main/photo/microintel-black-small.png)  

[Click to Read Summary](#summary)  

## Purpose of Sparrow  
In today's digital world, people rely on password managers, screenshots, and PDFs to store sensitive information. However, these solutions are often limited to passwords and pose security risks if a device is lost or stolen. Traditional password managers, PDFs, and galleries also have slow search capabilities. **Sparrow** was developed to solve these problems by allowing users to securely store all kinds of digital data with encryption. Unlike other managers, Sparrow hides data on the client device and enables fast searching for quick retrieval.  

## Introduction  
Sparrow is a **client-side** secure storage application for managing credentials, passwords, credit card details, and other sensitive data. It ensures security using two types of encryption:  
- **Sky Password**: Encrypts and decrypts individual data values.  
- **Breeze Password**: Encrypts and decrypts the entire file.  

### Example:  
```
Sky Password: DanielsKey123  
Breeze Password: DanielsEncryption987  
```

## Login  
To access Sparrow, the user must provide:  
- **Name**: User identification.  
- **File Input**: Encrypted file uploaded manually or via URL.  
- **Breeze Password**: Required to decrypt and access the file.  
- **Temporary PIN**: Session-based PIN, active until logout.  

### Example:  
```
Name: Daniels  
File: DanielsFile.sparrow  
Breeze Password: Daniels-Chakli987  
Temporary PIN: 5678  
```

## Black Sparrow  
Black Sparrow is responsible for creating and managing password files.  

### Required Inputs:  
- **Name**: Identification for the password file.  
- **Sky Password**: Encrypts individual stored values.  
- **Breeze Password**: Encrypts the entire file.  

### Example:  
```
Name: Daniels  
Sky Password: DanielsKey987  
Breeze Password: DanielsLock567  
Action: Create & Download Password File  
```

## White Sparrow  
White Sparrow manages secure data storage in key-value pairs.  

### Required Inputs:  
- **Sky Password**: Encrypts and decrypts stored values.  
- **Breeze Password**: Required to decrypt and access the file.  
- **Data Reference/ID**: Unique identifier for stored data.  
- **Data**: The actual credential, password, or information to be stored.  

### Example:  
```
Sky Password: DanielsKey987  
Breeze Password: DanielsLock567  
Data Reference: EmailLogin  
Data: Dani-Daniels.1234@email.com | DaniPass@1234  
```

## Sparrow Interface  
The Sparrow interface is a chat-like system where users can interact securely.  

### Features:  
- Retrieve stored credentials by asking questions.  
- Solve mathematical expressions within the interface.  
- Perform web searches by clicking the Earth icon.  
- View profile details, including Name, Sky, and Breeze passwords.  
- Logout to end the session and lock the encrypted file.  

### Example:  
```
User: Show my EmailLogin  
Sparrow: Dani-Daniels.1234@email.com | DanielsPass@1234  
User: 2 * 2?  
Sparrow: 4  
```

## Critical Security Notes  
The **Breeze password** and **encrypted file** must be stored securely. Losing them results in total data loss.  

### Recommended Backup Options:  
- Store on a USB drive.  
- Save in cloud storage.  
- Host securely on platforms like GitHub ([Read More](gitdoc.html)), Vercel, etc.  
- Send a backup via private messaging.  

If the Breeze password is lost, all data is permanently inaccessible.  

---

## Summary  

### Step 1 - Black Sparrow  
Create **password file**  
**Example:** `Vault, Sky123, Breeze456`  

### Step 2 - Login  
Enter **name, file, Breeze, PIN**  
**Example:** `John, data.sparrow, Secret123, 5678`  

### Step 3 - White Sparrow  
Store **key-value data**  
**Example:** `EmailLogin â†’ user@mail.com | Pass@123`  

### Step 4 - Sparrow UI  
**Chat to retrieve, calculate, search**  
**Example:** `Show EmailLogin â†’ user@mail.com`  

### Step 5 - Security  
**Backup Breeze & file**  
**Example:** `USB, Cloud, GitHub`  

**Documentation Created by:** AI With MicroIntel  
