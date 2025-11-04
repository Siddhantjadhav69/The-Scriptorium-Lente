
# 🕯️ The Scriptorium Lente *(The Slowest Story)*

**The Scriptorium Lente** is a single-page web application for **collaborative storytelling** — where stories unfold **one word at a time**.

It’s designed to celebrate patience, creativity, and collective imagination. Each user becomes a scribe, contributing their word to the growing tale — but only when it’s their turn.

---

## 🌿 Concept

> *“The Scriptorium is a place of patience.”*

In this app, storytelling is a slow art form. Every user is invited to write, but no one can rush the process.

### How It Works

1. **🌱 Plant a Seed:**
   Start a new story by writing the very first word.

2. **✍️ Add a Word:**
   Contribute a single word to any ongoing story.

3. **⏳ The Rule of Patience:**

   * You **cannot** add two consecutive words to the same story.
   * After writing a word, you must **wait** until another scribe adds the next one before contributing again.
   * This ensures collaboration and keeps the storytelling rhythm slow and mindful.

4. **🔄 Real-Time Updates:**
   All active stories update live for every user — no refresh needed.

---

## 🧠 Tech Stack

| Layer        | Technology              | Description                                                                    |
| ------------ | ----------------------- | ------------------------------------------------------------------------------ |
| **Frontend** | HTML5, Tailwind CSS     | Simple and elegant interface for reading and writing stories                   |
| **Backend**  | Firebase                | Serverless backend to handle logic and real-time updates                       |
| **Database** | Firestore (NoSQL)       | Stores stories and individual word contributions                               |
| **Auth**     | Firebase Authentication | Anonymous sign-in for unique user IDs (used to enforce *The Rule of Patience*) |

---

## ⚙️ Features

* Real-time collaborative word-by-word storytelling
* Anonymous user sessions (no accounts or sign-ups)
* Enforced patience through Firebase logic
* Minimalist, distraction-free interface

---

## 🚀 Getting Started

### Prerequisites

* A Firebase project (with Firestore & Authentication enabled)
* Node.js and Firebase CLI installed

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/the-scriptorium-lente.git
   ```
2. Navigate to the project folder:

   ```bash
   cd the-scriptorium-lente
   ```
3. Configure your Firebase settings in the app’s configuration file.
4. Deploy or run locally:

   ```bash
   firebase deploy
   ```

   or

   ```bash
   firebase serve
   ```

---

## 🌌 Philosophy

> *“Stories are not races to be finished.
> They are gardens to be tended.”*

The Scriptorium Lente invites you to slow down — to write, wait, and watch as stories bloom together over time.

---
