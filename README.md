# ERP System Architecture — Demo Interface

## 📌 Project Overview

This project is a lightweight front-end module simulating a basic **ERP (Enterprise Resource Planning)** system. It is built with **Bootstrap 5** and **jQuery**, showcasing core CRUD functionalities: **Create**, **Read**, **Update**, and **Delete**.

It serves as a foundational UI component for future integration with APIs, databases, or complete ERP back-end systems.

---

## 🧱 Tech Stack

| Category       | Technology                                  |
|----------------|---------------------------------------------|
| Front-End      | [Bootstrap 5.3.3](https://getbootstrap.com) |
| JavaScript     | [jQuery 3.7.1](https://jquery.com)          |
| Markup & Style | HTML, CSS, JavaScript                       |
| Responsive     | ✅ Fully responsive design                   |

---

## 🖥️ Features

- **Add Entry:** Input email and information, then add the entry to the table.
- **Edit Entry:** Click a table row to populate the input fields, then update the data.
- **Delete Entry:** Remove a specific row using the delete button.
- **Clear Inputs:** Reset the input fields with a single click.

---

## 🔁 Interaction Flow

```mermaid
graph TD
  A[Fill in Email/Info] --> B{Click Button}
  B -->|Add Data| C[Append Row to Table]
  B -->|Clear Input| D[Clear Fields]
  B -->|Edit| E[Update Selected Row]
  C --> F[Each Row Has Delete Button]
  F --> G[Remove Row]
  C --> H[Click Row]
  H --> I[Populate Input Fields]
