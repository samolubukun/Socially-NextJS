# Socially 🚀

[![Next.js](https://img.shields.io/badge/Next.js-14.x-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-2C3440?style=flat-square&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Clerk](https://img.shields.io/badge/Clerk-673AB7?style=flat-square&logo=clerk&logoColor=white)](https://clerk.com/)
[![UploadThing](https://img.shields.io/badge/UploadThing-000000?style=flat-square&logoColor=white)](https://uploadthing.com/)

**Socially** is a cutting-edge social media application meticulously crafted with **Next.js**. Experience seamless user interaction with features spanning authentication, dynamic post creation, engaging commenting and liking, real-time notifications, and comprehensive profile management. Dive into a codebase engineered for performance and scalability.

This project was inspired by and built following the [Next.js Tutorial 2025 - Build a Full Stack Social App with React & Next.js](https://youtu.be/vUYopHWOURg?si=J6ptvPg85ndzibMV).

## ✨ Key Features

* **User Authentication**: Secure sign-up, login, and intuitive profile management powered by Clerk.
* **Posts**: Effortlessly create, like, comment on, and delete posts. Engage with content like never before.
* **Notifications**: Stay in the loop with real-time notifications for likes, comments, and new followers.
* **Profiles**: Showcase your identity and view other user profiles seamlessly.
* **Follow System**: Connect and build your network by following and unfollowing other users.
* **Dark Mode**: Enjoy a comfortable browsing experience with a sleek light/dark theme toggle.

## 📸 Screenshots
![Screenshot (390)](https://github.com/user-attachments/assets/b5271d3f-18c5-4216-96af-5a6af0bc5174)
![Screenshot (391)](https://github.com/user-attachments/assets/f304e7dc-76f1-4001-a1cd-2e846a86263c)
![Screenshot (393)](https://github.com/user-attachments/assets/bf50ad10-0efe-4888-8dc4-089f4d21b744)
![Screenshot (392)](https://github.com/user-attachments/assets/561952b6-2d0d-4ec2-a3d8-93c8a57c82f6)
![Screenshot (395)](https://github.com/user-attachments/assets/222a793d-b635-4598-8fa9-65924ed3d0c0)
![Screenshot (394)](https://github.com/user-attachments/assets/5f8355f1-168e-4bd2-aa33-2523c5ce1b16)

## 🚀 Highlights

* **Blazing Fast Tech Stack**: Built with the latest **Next.js App Router**, robust **Postgres** database managed by **Prisma**, seamless authentication via **Clerk**, and strongly typed with **TypeScript**.
* **Next-Gen Architecture**: Leverages **Server Components**, **Layouts**, **Route Handlers**, and **Server Actions** for optimal performance and a streamlined development experience.
* **Robust Error Handling**: Graceful UI feedback with custom **`loading.tsx`**, **`error.tsx`**, and **`not-found.tsx`** components.
* **Seamless API Integration**: Efficient backend communication using **Route Handlers**.
* **Optimized Data Flow**: Smart **Data Fetching**, **Caching**, and **Revalidation** strategies for a responsive user interface.
* **Versatile Components**: A harmonious blend of interactive **Client Components** and performant **Server Components**.
* **Dynamic & Static Routing**: Flexible navigation powered by both **Dynamic** and **Static Routes**.
* **Elegant Styling**: Beautifully styled with **Tailwind CSS** and enhanced with **Shadcn** UI components.
* **Secure Authentication & Authorization**: Robust user management and security powered by Clerk.
* **Effortless File Uploads**: Integrated **UploadThing** for seamless and efficient file handling.
* **Reliable Database**: Type-safe database interactions with **Prisma**.
* **Interactive Forms**: Enhanced user experience with **Server Actions** for form submissions.
* **Instant UI Updates**: Implementations of **Optimistic Updates** for a fluid and responsive feel.

## 🛠️ Setup

To get Socially up and running on your local machine, follow these steps:

1.  Clone the repository:
    ```bash
    git clone <repository_url>
    cd socially
    ```

2.  Install the dependencies:
    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

3.  Set up your `.env` file by creating the file in the root directory and filling in your environment variables:

    ```env
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
    CLERK_SECRET_KEY=your_clerk_secret_key
    DATABASE_URL="postgresql://user:password@host:port/database"
    UPLOADTHING_TOKEN=your_uploadthing_secret
    ```

4.  Push the Prisma schema to your database and generate the Prisma client:
    ```bash
    npx prisma db push
    npx prisma generate
    ```

5.  Start the development server:
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.
