# 🔎 Lost and Found Management System

A simple **Lost and Found Management System** built using **n8n automation, Google Sheets, OpenAI, and Gmail**.

The project allows students to report an item they have **lost or found**. The information is automatically stored, processed by an AI assistant, and followed by a friendly confirmation email.

---

## 🎯 Project Purpose

Students often lose items such as:

- 🎒 Bags
- ✏️ Stationery
- 📚 Books
- 🧥 Clothes
- 🧢 Caps
- 🥤 Water bottles

This system makes reporting lost and found items easier and more organised.

---

## ⚙️ How It Works

### 1. Student Submits the Form

The student fills in information such as:

- Student name
- Email
- Item name
- Item colour
- Location
- Lost or Found
- Image of the item (optional)

### 2. Information Is Saved

The submitted information is automatically added or updated in a **Google Sheet**.

This creates an organised record of lost and found requests.

### 3. AI Creates a Response

An **OpenAI AI Agent** reads the submission.

If the student selected **Lost**, the AI confirms that the request has been recorded.

If the student selected **Found**, the AI thanks the student for submitting the found item.

### 4. Confirmation Email Is Sent

The system automatically sends a kid-friendly HTML email to the student's email address.

The email contains the AI-generated message and reminds students to hand found items to a teacher or the Lost & Found team.

---

## 🔄 Workflow

```text
Student
   ↓
Lost & Found Form
   ↓
Google Sheets
   ↓
OpenAI AI Agent
   ↓
JavaScript Processing
   ↓
Gmail
   ↓
📧 Confirmation Email
```

---

## 🛠️ Technologies Used

- **n8n** — Workflow automation
- **OpenAI** — Generates simple confirmation messages
- **Google Sheets** — Stores lost and found records
- **Gmail** — Sends confirmation emails
- **JavaScript** — Handles uploaded image data
- **HTML/CSS** — Creates the kid-friendly email design

---

## 🤖 Example

A student submits:

```text
Student Name: Rayhaan
Item: Water Bottle
Colour: Blue
Location: Playground
Status: Lost
```

The system records the information and automatically sends a confirmation message to the student.

---

## ✨ Features

- Report lost items
- Report found items
- Record student information
- Record where the item was lost or found
- Upload an image
- Automatically store information in Google Sheets
- AI-generated confirmation messages
- Automatic Gmail notifications
- Kid-friendly HTML email design

---

## 🚀 Future Improvements

Some features that could be added later:

- 🔍 Automatically match lost items with found items
- 📸 Compare uploaded item images
- 🔔 Notify students when a possible match is found
- 📊 Create a Lost & Found dashboard
- ✅ Mark items as returned
- 🗓️ Record the date an item was lost or found
- 🔐 Add an admin page for teachers

---

## 📁 Workflow File

The n8n workflow can be exported as a JSON file and stored in this repository.

Example:

```text
Lost and found.json
```

The workflow can then be imported into n8n.

> **Important:** Before sharing the workflow publicly, check the exported JSON and remove or replace any account-specific IDs, webhook information, document IDs, or other configuration details that you do not want to publish.

---

## 👨‍💻 Author

**Rayhaan**

Created as a learning project to explore:

**Automation + AI + Python/Coding Concepts + Real-World Problem Solving**

---

⭐ If you like this project, consider giving the repository a star!
