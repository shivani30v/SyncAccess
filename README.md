# **SyncAccess**  

## 📋 **Table of Contents**  
1. 🤖 [Overview](#overview)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🚀 [Quick Start](#quick-start)  

---

## 🤖 **Overview**  
SyncAccess is a real-time collaborative editor built with **Next.js**, styled with **TailwindCSS**, and powered by **Liveblocks**. It replicates the core features of Google Docs, allowing multiple users to collaborate on documents in real time. This project showcases developer expertise in building dynamic, collaborative environments.  

---

## ⚙️ **Tech Stack**  
- **Next.js**  
- **TypeScript**  
- **Liveblocks** (real-time collaboration)  
- **Lexical Editor**  
- **ShadCN** (UI components)  
- **Tailwind CSS**  

---

## 🔋 **Features**  
- **Authentication**:  
  Secure sign-in using GitHub with **NextAuth** for session management.  

- **Collaborative Text Editor**:  
  Real-time editing by multiple users.  

- **Document Management**:  
  - Create, delete, and list documents.  
  - Share via link or email with **view/edit permissions**.  

- **Comments**:  
  - Inline and general comments with threaded discussions.  

- **Real-time Presence**:  
  - View active collaborators in the editor.  

- **Notifications**:  
  Get alerts for shared documents, new comments, and collaborator actions.  

- **Responsive Design**:  
  Works seamlessly on all devices.  

---

## 🚀 **Quick Start**  
Follow these steps to set up the project locally.

### **Prerequisites**  
Ensure you have the following installed:  
- [Git](https://git-scm.com/)  
- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  

### **Clone the Repository**  
```bash
git clone https://github.com/shivani30v/SyncAccess.git
cd accessly
```

### **Install Dependencies**  
```bash
npm install
```

### **Set Up Environment Variables**  
1. Create a `.env` file in the project root.  
2. Add the following content:  
```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```
3. Replace the placeholder values with your **Clerk** and **Liveblocks** credentials:  
   - Get Clerk credentials from [Clerk](https://clerk.com/)  
   - Get Liveblocks credentials from [Liveblocks](https://liveblocks.io/)  

### **Run the Project**  
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to access the app in your browser.  

---