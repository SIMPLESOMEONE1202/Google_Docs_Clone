<div align="center"> <br /> <img src="public/readme/hero.png" alt="Project Banner" width="600" /> <h2 align="center">Storage & File Sharing Platform</h2> <p align="center">A personal project for managing, organizing, and sharing files effortlessly.</p> <div> <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs" alt="Next.js" /> <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" /> <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="TailwindCSS" /> <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="Appwrite" /> </div> </div>
📋 Table of Contents

About

Tech Stack

Features

Installation & Setup

Usage

Project Structure

Credits

🔹 About

This is a personal project designed to simplify file management and sharing. Users can securely upload, organize, download, and share files. It is built with Next.js, TypeScript, TailwindCSS, and Appwrite for backend storage and authentication.

This project helped me explore modern React architecture, state management, responsive UI design, and cloud storage integration.

⚙️ Tech Stack

Frontend: React 19, Next.js 15, TailwindCSS, ShadCN

Backend: Appwrite (Authentication & Storage)

Language: TypeScript

🔋 Features

User Authentication: Signup, login, logout, and account management.

File Uploads: Upload documents, images, videos, and audio files.

File Management: View, rename, delete, or download files.

File Sharing: Share files securely with other users.

Dashboard: Track storage usage, recent uploads, and file types at a glance.

Search & Sorting: Quickly search files and sort by name, date, or size.

Responsive Design: Works smoothly on desktop and mobile devices.

🛠️ Installation & Setup

Clone the repository:

git clone https://github.com/<YOUR_USERNAME>/Google_Docs_Clone.git
cd Google_Docs_Clone


Install dependencies:

npm install


Configure environment variables by creating a .env.local file:

NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""


Run the development server:

npm run dev


Open http://localhost:3000
 to view your project.

🚀 Usage

Upload and organize files in the dashboard.

Share files with others by entering their email addresses.

Track your storage usage and recent activity.

📂 Project Structure
/components  - Reusable UI components
/pages       - Next.js pages
/lib         - Utility functions
/constants   - Static configs like navItems, actions, etc.
/public      - Static assets & images
/styles      - TailwindCSS configuration

🎯 Credits

Built as a personal learning and portfolio project.

Powered by Next.js, Appwrite, TypeScript, and TailwindCSS.