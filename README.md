---

## **Project Name: WhatsAppClone**

WhatsAppClone is a full-stack web application built using **Next.js**, **TypeScript**, and **Convex** backend. It replicates the features of a real-time messaging app, enabling users to engage in private/group chats, send multimedia messages, interact with OpenAI APIs for chat completions and image generation, and initiate video calls with screen sharing.

---

### **Mission and Objectives for WhatsAppClone**

---

### **Mission:**
To create a modern, responsive, and feature-rich messaging application that supports real-time communication, integrates AI-powered functionalities, and provides a seamless user experience.

---

### **Objectives:**
1. **User Authentication:**
   - Implement secure authentication using **Clerk**.
   - Manage user sessions and profiles seamlessly.

2. **Messaging System:**
   - Enable private and group chats with message types: text, emoji, image, and video.
   - Display real-time updates for online status and message delivery.

3. **AI Integration:**
   - Add chat completions using **OpenAI's GPT** model.
   - Generate images through **OpenAI's DALL·E** API.

4. **Video Calling:**
   - Integrate video conferencing with **screen sharing** and adjustable layouts.
   - Allow users to create sharable room links for meetings.

5. **Responsive Design:**
   - Ensure a mobile-friendly, intuitive interface with light/dark mode support.

6. **Backend and Real-Time Features:**
   - Utilize **Convex** for real-time updates, database storage, and server-side operations.

7. **Deployment:**
   - Deploy the fully functional app for public accessibility.

---

## **Technology Stack**

### **Frontend**
1. **Next.js**
   - **Why:** A React framework for server-side rendering and performance optimization.
   - **Use Case:** Building a scalable and efficient UI with routing and API support.

2. **TypeScript**
   - **Why:** Adds type safety, reducing bugs and improving maintainability.
   - **Use Case:** Ensures predictable and robust development for complex features.

3. **Tailwind CSS**
   - **Why:** Utility-first CSS framework for rapid and responsive design.
   - **Use Case:** Styling components, light/dark themes, and custom layouts.

4. **ShadCN UI**
   - **Why:** Pre-built accessible components for fast UI development.
   - **Use Case:** Dialogs, buttons, inputs, and modals.

---

### **Backend**
1. **Convex**
   - **Why:** Provides real-time database and serverless backend services.
   - **Use Case:** Stores messages, user data, and group details with real-time synchronization.

2. **OpenAI API**
   - **Why:** Leverages GPT for chat completions and DALL·E for image generation.
   - **Use Case:** AI-powered responses and multimedia generation in chats.

3. **WebSockets**
   - **Why:** Ensures instant message delivery and updates.
   - **Use Case:** Powers real-time chat, status updates, and video call signaling.

---

### **Authentication**
1. **Clerk**
   - **Why:** A user-friendly authentication solution with pre-built UI components.
   - **Use Case:** Manages user login, registration, and profile management.

---

### **Deployment**
1. **Frontend Hosting:** Vercel
   - **Why:** Optimized for Next.js applications.
   - **Use Case:** Deploys the client-side application for global access.

2. **Backend Hosting:** Convex (serverless backend)
   - **Why:** Provides real-time backend with automatic scalability.
   - **Use Case:** Hosts API services and stores application data.

---

## **Workflow Overview**
This section illustrates the core workflows of **WhatsAppClone**:
1. **User Authentication:** Secure login and profile management using Clerk.
2. **Real-Time Messaging:** Private/group chats with multimedia support.
3. **AI-Powered Responses:** Integration with OpenAI APIs for text and image generation.
4. **Video Calling:** Real-time conferencing with screen sharing capabilities.
5. **Data Management:** Backend operations using Convex for real-time storage and updates.
6. **UI/UX:** Responsive and intuitive design with dynamic light/dark themes.

---

### **System Architecture**
The system architecture highlights the interaction between the frontend, backend, and external services:
- **Frontend:** Next.js and TypeScript.
- **Backend:** Convex for data storage and real-time features.
- **APIs:** OpenAI for AI functionalities.
- **Deployment:** Vercel for the frontend and Convex for backend hosting.

![image](https://github.com/user-attachments/assets/c9093c2f-d83d-4bd3-8c64-499558f72032)
![Screenshot (320)](https://github.com/user-attachments/assets/c0a0a980-8604-466f-9a34-40b693cbb2f7)


---

## **Week-by-Week Plan**

### **Week 1: Project Setup and UI Design**
- **Goal:** Set up the foundational structure and design the app UI.
- **Tasks:**
  1. Initialize a **Next.js** project with TypeScript and Tailwind CSS.
     - **Reading:** [Next.js TypeScript Setup](https://nextjs.org/docs/basic-features/typescript)  
     - **Video:** [Setting Up Next.js with Tailwind](https://www.youtube.com/watch?v=ZVnjOPwW4ZA&t=114s)
  2. Integrate **ShadCN UI** for pre-built components.
     - **Reading:** [ShadCN UI Docs](https://ui.shadcn.com/docs)  
     - **Video:** [ShadCN Components Setup](https://www.youtube.com/watch?v=O4AjymzpIEg&t=162s)
  3. Build the **light/dark mode** toggle feature.
     - **Reading:** [Dark Mode in Tailwind](https://tailwindcss.com/docs/dark-mode)  
     - **Video:** [Tailwind Dark Mode Guide](https://www.youtube.com/watch?v=_9mTJ84uL1Q)

- **Deliverables:**
  - Fully responsive UI layout with light/dark mode support.

---

### **Week 2: User Authentication**
- **Goal:** Set up secure user authentication.
- **Tasks:**
  1. Integrate **Clerk** for user login/signup.
     - **Reading:** [Clerk Authentication Docs](https://clerk.com/docs)  
     - **Video:** [Clerk Authentication Setup](https://www.youtube.com/watch?v=-4NcENXw-iw)
  2. Implement protected routes for authenticated users.
     - **Reading:** [Protected Routes in Next.js](https://next-auth.js.org/tutorials/securing-pages-and-api-routes)  
     - **Video:** [Route Protection](https://www.youtube.com/watch?v=Fx8c3dQD_TI)

- **Deliverables:**
  - Functional authentication system with user profiles.

---

### **Week 3: Real-Time Messaging**
- **Goal:** Build core messaging functionality.
- **Tasks:**
  1. Set up a **Convex** database for storing messages and conversations.
     - **Reading:** [Convex Quickstart Guide](https://docs.convex.dev/quickstart)  
     - **Video:** [Getting Started with Convex](https://www.youtube.com/watch?v=vaQZYRSiimI)
  2. Implement private and group chat functionalities.
     - **Reading:** [Real-Time Messaging with Convex](https://docs.convex.dev/tutorial)  
     - **Video:** [Building Real-Time Apps](https://www.youtube.com/watch?v=O_HXVAMPEbc)
  3. Display **online status** and message delivery indicators.
     - **Reading:** [State Management with Convex](https://docs.convex.dev/)  
     - **Video:** [Building User Presence](https://www.youtube.com/watch?v=WyS3mF4wJKw)

- **Deliverables:**
  - Real-time messaging system with group support.

---

### **Week 4: AI Integration**
- **Goal:** Add OpenAI-powered chat and image generation features.
- **Tasks:**
  1. Integrate **OpenAI GPT API** for chat responses.
     - **Reading:** [OpenAI API Documentation](https://platform.openai.com/docs/)  
     - **Video:** [Integrating OpenAI APIs](https://www.youtube.com/watch?v=7pV_TCCK3Hw)
  2. Implement image generation using **DALL·E API**.
     - **Reading:** [DALL·E API Overview](https://platform.openai.com/docs/guides/images)  
     - **Video:** [DALL·E Image Generation](https://www.youtube.com/watch?v=hSe_HWLn6Wg)

- **Deliverables:**
  - AI-powered chat completions and image generation.

---

### **Week 5: Video Calling and Deployment**
- **Goal:** Add video calling features and deploy the app.
- **Tasks:**
  1. Implement video calling with **screen sharing**.
     - **Reading:** [WebRTC Video Calling Guide](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)  
     - **Video:** [Building Video Conferencing Apps](https://www.youtube.com/watch?v=pGAp5rxv6II)
  2. Deploy the application using **Vercel**.
     - **Reading:** [Deploying Next.js Apps](https://vercel.com/docs)  
     - **Video:** [Vercel Deployment Tutorial](https://www.youtube.com/watch?v=2HBIzEx6IZA)

- **Deliverables:**
  - Fully functional WhatsAppClone app deployed and publicly accessible.

---

### **Screenshots**

![Screenshot (308)](https://github.com/user-attachments/assets/6e614462-7b64-48a4-9cc1-b5eb6bae903f)
![Screenshot (309)](https://github.com/user-attachments/assets/55c690f7-3f83-47d0-b5dd-0620513d3f33)
![Screenshot (310)](https://github.com/user-attachments/assets/a4550c83-7d85-4204-8659-369d7a8d7805)
![Screenshot (311)](https://github.com/user-attachments/assets/79088240-af14-4d87-abfb-78099ea1d4e7)
![Screenshot (312)](https://github.com/user-attachments/assets/562f2fcd-dfaf-4a06-9dc9-c64a594e8066)
![Screenshot (314)](https://github.com/user-attachments/assets/2b6cd021-dd56-47fa-b691-966e9dfbe3cf)
![Screenshot (315)](https://github.com/user-attachments/assets/a0a22b6d-c16e-430a-90fd-5b727f196ea2)
![Screenshot (316)](https://github.com/user-attachments/assets/ec8be976-a55f-414f-82c1-f0323089758e)
![Screenshot (317)](https://github.com/user-attachments/assets/44e6836e-3a30-4ae4-af88-1cc162e42914)
![Screenshot (318)](https://github.com/user-attachments/assets/3b7ae655-d585-47e7-8280-b1fcd85046b3)
![Screenshot (302)](https://github.com/user-attachments/assets/a7881c36-5cfa-4ac4-9f32-41cd36716268)
![Screenshot (306)](https://github.com/user-attachments/assets/6d47f1d9-3e5b-493e-81f3-60690f4c85c9)

---

## **References**
1. [Next.js Documentation](https://nextjs.org/docs)
2. [Convex Docs](https://docs.convex.dev)
3. [Clerk Authentication](https://clerk.com/docs)
4. [OpenAI APIs](https://platform.openai.com/docs)
5. [Tailwind CSS Docs](https://tailwindcss.com/docs)
6. [ShadCN UI](https://ui.shadcn.com/docs)
7. https://www.youtube.com/watch?v=sQ1zvdS8eU8
8. https://github.com/burakorkmez/whatsapp-clone

---
