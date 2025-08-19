# Socialink 🔗💬

![Desktop Demo](./public/readme-screenshot.png)

## 📌 Table of Contents

- [Socialink 🔗💬](#socialink-)
  - [📌 Table of Contents](#-table-of-contents)
  - [🌐 Overview](#-overview)
  - [⚙️ Features](#️-features)
  - [💻 Technologies Used](#-technologies-used)
  - [🗝️ Key Takeaways](#️-key-takeaways)
  - [🚀 How to Run the Project](#-how-to-run-the-project)
  - [🤝 Contributing](#-contributing)
  - [💬 Contact](#-contact)

## 🌐 Overview

**Socialink** is a modern mini social network where users can create posts, follow others, like, comment, and receive notifications.  
Built with **Next.js App Router**, **Prisma**, and **Postgres**, it showcases a full-stack approach with server components, server actions, and secure authentication via **Clerk**.  
The project focuses on **scalability, responsiveness, and user experience**.

## ⚙️ Features

- 📝 **Posts** – Create text posts with optional image uploads.
- 👥 **Follow System** – Follow/unfollow users with instant notifications.
- ❤️ **Likes & Comments** – Engage with posts, each action triggers notifications.
- 🔔 **Notifications** – Real-time updates for new followers, likes, and comments.
- ✏️ **Profile Editing** – Update name, bio, website, and location.
- 🌱 **Suggestions** – “Who to follow” widget with dynamic recommendations.
- ⚡ **Optimistic UI** – Fast, responsive interactions with server revalidation.

## 💻 Technologies Used

- [Next.js (App Router)](https://nextjs.org/) – Server components, server actions, route handlers.
- [React](https://react.dev/) – Client interactivity where needed.
- [TypeScript](https://www.typescriptlang.org/) – Strong typing for scalability and safety.
- [Clerk](https://clerk.com/) – Authentication and user management.
- [Prisma](https://www.prisma.io/) + [Postgres](https://www.postgresql.org/) – Database and ORM for structured data.
- [UploadThing](https://uploadthing.com/) – Secure image uploads.
- [Tailwind CSS](https://tailwindcss.com/) + [ShadCN UI](https://ui.shadcn.dev/) + [Radix UI](https://www.radix-ui.com/) – Styling and accessible UI components.
- [Lucide Icons](https://lucide.dev/) – Clean and lightweight icon set.

## 🗝️ Key Takeaways

1. **Full-Stack with Next.js App Router** – Seamless server/client integration.
2. **Transactional Database Operations** – Ensuring data integrity (likes + notifications).
3. **Authentication via Clerk** – Production-ready auth, easy integration.
4. **Optimistic UI & Revalidation** – Better UX without sacrificing consistency.
5. **Scalable & Clean Design** – Tailwind + Shadcn UI deliver modern UI quickly.

## 🚀 How to Run the Project

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Cauebf/socialink.git
   cd socialink
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up environment variables**:

   Create a `.env` file in the root directory and add the following variables:

   ```env
   # Clerk Auth
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key

   # Prisma / Postgres
   DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE

   # UploadThing
   UPLOADTHING_TOKEN=your_uploadthing_token
   ```

4. **Set up Prisma and the database**:

   ```bash
   npx prisma generate
   npx prisma migrate dev --name init
   ```

5. **Start the development server**:

   ```bash
   npm run dev
   ```

6. **Build the app for production**:

   ```bash
   npm run build
   npm start
   ```

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

## 💬 Contact

For any inquiries or collaboration opportunities, feel free to reach out via:

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cauebrolesef@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cauebrolesef/)
[![Instagram](https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/cauebf_/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Cauebf)

<p align="right">(<a href="#socialink-">back to top</a>)</p>
