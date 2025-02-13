🧠 Podcastr
AI Podcast Platform - A cutting-edge AI SaaS platform that enables users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail image generation, and seamless playback.

📋 Table of Contents
Organize the README to make it easy to navigate.

🤖 Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start
🕸️ Snippets (Code to Copy)
🔗 Assets
🚀 More
🚨 Tutorial

🤖 Introduction
A platform that transforms written content into podcasts using advanced AI. Users can explore new podcasts, create their own using text-to-audio conversion, and enjoy a seamless listening experience with a modern podcast player.

⚙️ Tech Stack

Next.js
TypeScript
Tailwind CSS
OpenAI
Clerk
Convex
ShadCN

🔋 Features

👉 Robust Authentication: Secure user login and registration.
👉 Modern Home Page: Showcases trending podcasts with continuous listening.
👉 Create Podcast Page: Enables text-to-audio conversion, AI image generation, and previews.
👉 Multi-Voice AI: Dynamic podcast creation with multiple AI-generated voices.
👉 Fully Responsive Design: Visually appealing on all devices.

🤸 Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/adrianhajdin/jsm_podcastr.git
cd jsm_podcastr
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
Replace the placeholder values with your actual Convex & Clerk credentials. You can obtain these credentials by signing up on the Convex and Clerk websites.

Running the Project

npm run dev
Open http://localhost:3000 in your browser to view the project.
