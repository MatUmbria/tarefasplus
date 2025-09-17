# 📌 Tarefas+

Web application for task management with support for **private tasks** (no comments) and **public tasks** (allowing comments from logged-in users).  

## 🚀 Technologies

- [Next.js](https://nextjs.org/) with **TypeScript**  
- [NextAuth.js](https://next-auth.js.org/) for authentication (Google OAuth)  
- [Firebase Firestore](https://firebase.google.com/docs/firestore) as database  
- [React Icons](https://react-icons.github.io/react-icons/) for icons  
- [React 18](https://react.dev/)  

---

## ✨ Features

- 🔑 **Login with NextAuth** (Google OAuth)  
- 📝 Create **private tasks** (only visible to the owner)  
- 🌍 Create **public tasks** (visible to everyone)  
- 💬 **Comments** on public tasks (only logged-in users can comment)  
- ⚡ Hybrid rendering with **SSR (ServerSideProps)** and **SSG (GetStaticProps)**  

---

## 📂 Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/tarefas-plus.git
cd tarefas-plus
```

### 2. Install dependencies

#### Core dependencies
```bash
npm install next@13.5.11 react@18 react-dom@18 firebase@^12.2.1 next-auth@^4.24.11 react-icons@^5.5.0
```


### 3. Configure environment variables  
Create a **`.env.local`** file in the project root and add your keys:

```bash
# Firebase
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

# NextAuth
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
NEXTAUTH_URL=
NEXTAUTH_SECRET=
NEXT_PUBLIC_URL=
```

---

### 4. Run the project
```bash
npm run dev
```

The app will be available at [http://localhost:3000](http://localhost:3000).

---

## 🌐 Deploy

The project is hosted on Vercel:  
👉 [Tarefas+ - Vercel Deploy](https://your-vercel-link.vercel.app)

---


## 📌 Project status
✅ In development  

---
