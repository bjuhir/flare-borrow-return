# 🧾 BorrowReturn Smart Contract

A simple and beginner-friendly borrowing system built in Solidity.  
Created and maintained by **Juhir**.

---

## 📌 Project Description

BorrowReturn is a lightweight smart contract that demonstrates how to manage items using **structs**, **mappings**, and **basic access control** in Solidity.  
It allows the owner to add items and lets any user borrow and return them securely.

This project is perfect for beginners learning how state changes and user permissions work on Ethereum.

---

## 🚀 What It Does

- Lets the **owner** add new items  
- Allows **any user** to borrow an available item  
- Ensures **only the borrower** can return an item  
- Lets anyone check whether an item is currently **available or borrowed**

---

## ⭐ Features

### 🔹 Add Items
The owner can add new items. Each item gets a unique ID.

### 🔹 Borrow Items
Any user can borrow an item if it’s available (`borrower = address(0)`).

### 🔹 Return Items
Only the original borrower of an item can return it.

### 🔹 Check Availability
A public view function lets users check whether an item is available.

---

## 🔗 Deployed Smart Contract

**Contract Address:**  
`0x37e55d01a2c76831da3d5c67bf8c4fcb45257890940312d5f31677562a9d39a5`

"https://coston2-explorer.flare.network//tx/0x37e55d01a2c76831da3d5c67bf8c4fcb45257890940312d5f31677562a9d39a5"

---

