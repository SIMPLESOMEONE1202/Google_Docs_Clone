# Storage Management & File Sharing Platform

A personal project to manage, upload, and share files efficiently. Built with **Next.js 15**, **TypeScript**, **TailwindCSS**, and **Appwrite**.

---

## 📝 Table of Contents

1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Setup & Run](#setup--run)  
5. [Folder Structure](#folder-structure)  
6. [Utilities & Snippets](#utilities--snippets)  

---

## 🤖 Introduction

This project allows users to:

- Upload files of different types (documents, images, videos, audio).  
- View, rename, delete, and download files.  
- Share files with others via email.  
- Track storage usage with a dynamic dashboard.  
- Search and sort files efficiently.  

It’s built as a **personal project** to explore modern web development practices using Next.js and Appwrite.

---

## 🔋 Features

- **User Authentication** with Appwrite.  
- **File Upload & Management**: Upload, rename, delete, download files.  
- **File Sharing**: Share files securely with other users.  
- **Dashboard**: Track storage usage, recent uploads, and file summaries.  
- **Global Search & Sorting**: Quickly find and organize files.  
- **Responsive & Modern UI** with TailwindCSS and ShadCN.  

---

## ⚙️ Tech Stack

- **Frontend**: React 19, Next.js 15, TypeScript, TailwindCSS, ShadCN  
- **Backend / Storage**: Appwrite (authentication, database, file storage)  

---

## 🤸 Setup & Run

### Prerequisites

- [Node.js](https://nodejs.org/en/)  
- [npm](https://www.npmjs.com/)  
- [Git](https://git-scm.com/)  

### Steps

bash
# Clone repo
git clone https://github.com/YourUsername/YourRepo.git
cd YourRepo

# Install dependencies
npm install

# Setup environment variables
# Create .env.local in project root with the following:

NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""

# Replace values with your Appwrite project credentials

# Run project
npm run dev
Open http://localhost:3000 to view the project.



🗂 Folder Structure
/components   # Reusable React components
/pages        # Next.js pages
/public       # Static assets (images, icons)
/styles       # TailwindCSS & global styles
/lib          # Utility functions
/constants    # Project constants

⚡ Utilities & Snippets

File Size Converter

Date & Time Formatter

File Type & Icon Helpers

Appwrite File URL Generator

🚀 More

This project is for learning and personal use. You can extend it to include:

Multi-user collaboration

Advanced file versioning

Notifications & real-time updates

Made with ❤️ using Next.js, TypeScript, TailwindCSS, and Appwrite.
