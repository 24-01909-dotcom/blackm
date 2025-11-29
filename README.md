<div align="center">

# PAHINA'T GUNITA

**PAHINA'T GUNITA**  

<div align="center">

<b>IT-2108:</b><br>
GRECIA, JAMES BENEDICT P.<br>
PANALIGAN, MICHAELA C.<br>
REBENQUE, RHONE PAULENE P.<br>
</div>

---
<p align="center">
  <a href="#-overview">
    <img src="C:\Users\justi\OneDrive\Desktop\Final Proj\PIC\📖_Overview-6b4f29.svg">
  </a>
  <a href="#-key-features">
    <img src="https://img.shields.io/badge/⭐_Features-8c6931?style=for-the-badge">
  </a>
  <a href="#-gameplay-guide">
    <img src="https://img.shields.io/badge/🎮_Gameplay_Guide-b8863b?style=for-the-badge">
  </a>
  <a href="#-program-structure">
    <img src="https://img.shields.io/badge/🏗️_Program_Structure-d4a15f?style=for-the-badge">
  </a>
  <a href="#-how-to-run">
    <img src="https://img.shields.io/badge/🚀_How_to_Run-e3b679?style=for-the-badge">
  </a>
  <a href="#-sample-output">
    <img src="https://img.shields.io/badge/📜_Sample_Output-efcb9f?style=for-the-badge">
  </a>
  <a href="#-author--acknowledgement">
---
## 📖 Overview

**PAHINA’T GUNITA (Freedom Wall App) is a Java-based console application that allows users to anonymously express their thoughts through:
- **Letters
- **Confessions
- **Rants
- **The system demonstrates core Object-Oriented Programming (OOP) principles such as
- **Encapsulation
- **Inheritance
- **Abstraction
- **Polymorphism

---

All posts are saved in a local .txt file and can be viewed, searched, or removed using simple admin tools.

🚀 Features
✅ Anonymous Posting

Users may create posts of three types:

Letter
Confession
Rant

✅ Admin Tools

Protected by a simple password: ARIZONA_B

Admin features include:
View all posts (newest to oldest)
Read a specific post
Delete a specific post
Delete all posts

✅ Search Function

Search posts by keyword (case-insensitive).

✅ Automatic Saving

All posts are safely stored in: Freedom_Wall_posts.txt

✅ Persistent Storage

Loading and saving of:

ID
Type
Timestamp
Content

With escape-handling for pipes and backslashes.

🛠️ Technologies Used

Java (Core)
java.io – file read/write
java.time – timestamps
java.util – collections and scanner


📂 Project Structure
FreedomWallApp.java
 ├── FreedomWallApp (main class)
 ├── PahinatGunita (system controller)
 ├── Post (abstract class)
 ├── Letter (subclass)
 ├── Confession (subclass)
 └── Rant (subclass)
Freedom_Wall_posts.txt (generated at runtime)

▶️ How to Run

Open your IDE or terminal.

Compile:

javac FreedomWallApp.java

Run:

java FreedomWallApp

Press Enter when prompted.

Type YES to start or NO to exit.

🔐 Admin Mode

To view or delete posts:
When asked for password, enter: ARIZONA_B

🧩 OOP Concepts Used
Encapsulation

Private fields: id, content, timestamp

Controlled access via getters/setters

Inheritance

Letter, Confession, and Rant inherit from Post

Abstraction

Post is an abstract class; subclasses implement getType()

Polymorphism

Custom display formats for each post type

Overridden getType() method per subclass

💾 Data Storage Format

Each line in Freedom_Wall_posts.txt contains:

id|type|timestamp|content


Pipes (|) and backslashes (\) inside content are safely escaped.

📸 Sample Output
=== PAHINA'T GUNITA ===
Do you want to continue? YES or NO:
ANSWER: yes

1) Create a Post
2) View All Posts (admin)
3) Search Posts by Keyword
4) Delete a Post (admin)
5) Save & Exit

👤 Author

<div align="center">

<b>IT-2108:</b><br>
GRECIA, JAMES BENEDICT P.<br>
PANALIGAN, MICHAELA C.<br>
REBENQUE, RHONE PAULENE P.<br>
</div>
Java OOP Project – Freedom Wall System

📜 License

This project is for educational purposes. You may modify and improve it as needed.
