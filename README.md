<div align="center">
  <br />
      <img src="https://github.com/adrianhajdin/jsm_podcastr/assets/151519281/f61a58c2-f144-41f7-8bc9-5ad14752ceb3" alt="Project Banner">
  <br />
</div>

  <div>
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Next_._JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-OpenAI-black?style=for-the-badge&logoColor=white&logo=openai&color=412991" alt="openai" />
  </div>

# 🎙️ AI Podcast Platform  

## 📋 Table of Contents  

1. 🤖 [Introduction](#-introduction)  
2. ⚙️ [Tech Stack](#-tech-stack)  
3. 🔋 [Features](#-features)  
4. 🤸 [Quick Start](#-quick-start)  

## 🤖 Introduction  

The **AI Podcast Platform** is a state-of-the-art AI SaaS platform that empowers users to **create**, **discover**, and **enjoy podcasts**. It offers advanced features like **text-to-audio conversion** with multi-voice AI, **podcast thumbnail generation**, and seamless playback functionality.

## ⚙️ Tech Stack  

- **Next.js**  
- **TypeScript**  
- **Convex**  
- **OpenAI**  
- **Clerk**  
- **ShadCN**  
- **Tailwind CSS**  

## 🔋 Features  

- **👉 Robust Authentication**: Secure user login and registration system powered by Clerk.  
- **👉 Modern Home Page**: Displays trending podcasts with a **sticky podcast player** for uninterrupted listening.  
- **👉 Discover Podcasts Page**: Dedicated section to explore new and popular podcasts.  
- **👉 Fully Functional Search**: Allows users to search for podcasts using various criteria.  
- **👉 Create Podcast Page**:  
  - Text-to-audio podcast creation.  
  - AI-generated podcast thumbnails.  
  - Preview functionality for content before publishing.  
- **👉 Multi-Voice AI Functionality**: Leverages AI to create podcasts with multiple voice options.  
- **👉 Profile Page**: View all created podcasts and manage them (e.g., delete podcasts).  
- **👉 Podcast Details Page**:  
  - Displays creator information.  
  - Includes listener stats and transcript details.  
- **👉 Podcast Player**: Advanced controls for forward/backward, mute/unmute functionality, and smooth playback.  
- **👉 Responsive Design**: Fully optimized for all devices and screen sizes.  
- **👉 Code Architecture**: Built with reusable and scalable components.  

## 🤸 Quick Start  

Follow these steps to set up the project locally:  

### **Prerequisites**  
Ensure the following are installed on your system:  
- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  

### **Cloning the Repository**  
Clone the project and navigate into the directory:  
```bash  
git clone https://github.com/adrianhajdin/jsm_podcastr.git  
cd jsm_podcastr  
```  

### **Installation**  
Install the required dependencies:  
```bash  
npm install  
```  

### **Set Up Environment Variables**  
Create a `.env` file in the root directory and add the following:  
```env  
CONVEX_DEPLOYMENT=  
NEXT_PUBLIC_CONVEX_URL=  
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=  
CLERK_SECRET_KEY=  
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'  
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'  
```  
Replace the placeholders with your **Convex** and **Clerk** credentials, which can be obtained from their official websites:  
- [Convex](https://www.convex.dev/)  
- [Clerk](https://clerk.com/)  

### **Running the Project**  
Start the development server:  
```bash  
npm run dev  
```  
Access the application at **[http://localhost:3000](http://localhost:3000)** in your web browser.  

### 💡 Happy Podcasting!  
Feel free to report issues or contribute to enhance this project!  
