The Scriptorium Lente (The Slowest Story)

This repository contains the complete code for "The Scriptorium Lente," a single-page web application for collaborative storytelling. The core concept is a "slow story," where users contribute to tales one word at a time.

This app is built to be simple, elegant, and run on a serverless backend.

How It Works

The Scriptorium is a place of patience.

Plant a Seed: Any user can start a new story by writing the first word.

Add a Word: Any user can add a word to any existing story.

The Rule of Patience: A user cannot add a word to a story if they were the last person to contribute. They must wait for another scribe to add a word before they can contribute to that same story again. This encourages collective participation and slows down the creative process.

All stories are updated in real-time for all users.

Tech Stack

Frontend: HTML5, Tailwind CSS

Backend: Firebase

Firestore: A NoSQL database used to store the stories and their words.

Firebase Authentication: Used for Anonymous sign-in to assign a unique, stable ID (currentUserId) to each visitor, which enforces the "Rule of Patience."
