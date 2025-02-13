

# Podcastr 
AI Podcast Platform - A cutting-edge AI SaaS platform that enables users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail image generation, and seamless playback.

---

## 📋 Table of Contents  
- [🤖 Introduction](#-introduction)  
- [⚙️ Tech Stack](#️-tech-stack)  
- [🔋 Features](#-features)  
- [🤸 Quick Start](#-quick-start)  
- [🎨 Design Considerations](#-design-considerations)  

---

## 🤖 Introduction  
A cutting-edge AI SaaS platform that enables users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail image generation, and seamless playback.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 34k+ members. It's a place where people help each other out.

---

## ⚙️ Tech Stack  
- Next.js  
- TypeScript  
- Tailwind CSS  
- OpenAI  
- Clerk  
- Convex  
- ShadCN  

---

## 🔋 Features  
- 👉 **Robust Authentication:** Secure and reliable user login and registration system.  
- 👉 **Modern Home Page:** Showcases trending podcasts with a sticky podcast player for continuous listening.  
- 👉 **Discover Podcasts Page:** Dedicated page for users to explore new and popular podcasts.  
- 👉 **Fully Functional Search:** Allows users to find podcasts easily using various search criteria.  
- 👉 **Create Podcast Page:** Enables podcast creation with text-to-audio conversion, AI image generation, and previews.  
- 👉 **Multi Voice AI Functionality:** Supports multiple AI-generated voices for dynamic podcast creation.  
- 👉 **Profile Page:** View all created podcasts with options to delete them.  
- 👉 **Podcast Details Page:** Displays detailed information about each podcast, including creator details, number of listeners, and transcript.  
- 👉 **Podcast Player:** Features backward/forward controls, as well as mute/unmute functionality for a seamless listening experience.  
- 👉 **Responsive Design:** Fully functional and visually appealing across all devices and screen sizes.  

---

## 🤸 Quick Start  
Follow these steps to set up the project locally on your machine.

### Prerequisites  
Make sure you have the following installed on your machine:  
- Git  
- Node.js  
- npm (Node Package Manager)  

### Cloning the Repository  
```sh
git clone <repository-url>
cd <project-folder>
```

### Installation  
Install the project dependencies using npm:  
```sh
npm install
```

### Set Up Environment Variables  
Create a new file named `.env` in the root of your project and add the following content:  
```env
CONVEX_DEPLOYMENT=  
NEXT_PUBLIC_CONVEX_URL=  
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=  
CLERK_SECRET_KEY=  
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'  
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'  
```
Replace the placeholder values with your actual Convex & Clerk credentials.

### Running the Project  
```sh
npm run dev
```
Open `http://localhost:3000` in your browser to view the project.  

---



## 🎨 Design Considerations  
(https://www.figma.com/design/oNDghANb9Swr6K4nynQ1BF/Podcastr---AI-Podcast-App?node-id=0-1&t=d2OAPK0ZagFAxqFm-1)


