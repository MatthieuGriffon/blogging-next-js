Next.js Blogging Platform

This repository contains a blogging platform developed using Next.js, TailwindCSS, and PostgreSQL. The project is structured as a monolithic application, with Next.js handling both the frontend and backend through its API routes feature.

Features
Authentication and Authorization: Implemented using NextAuth.js, allowing for email/password authentication and role-based authorization.

User Roles: Two distinct user roles - Admin and User. Admins have the ability to manage all posts and user accounts, while Users can create, edit, and delete their own posts.

Blog Post Management: Create, update, and delete blog posts with a simple and intuitive UI.

Comments and Reactions: Users can comment on posts and give them a thumbs up or thumbs down.

Responsive Design: Tailored for a variety of devices using TailwindCSS.

Database: Utilizes PostgreSQL for data persistence, managed through the Prisma ORM.

TypeScript: Strongly typed codebase for enhanced development experience and error prevention.

Technical Stack

Frontend: Next.js with TailwindCSS for styling.

Backend: Next.js API routes for server-side logic.

Database: PostgreSQL with Prisma ORM for data management.

Authentication: NextAuth.js for session management and authentication.

ID Generation: UUID for generating unique identifiers.

Password Encryption: bcrypt.js for password hashing and verification.

Setup and Installation

Detailed setup and installation instructions will be provided to get the project up and running on your local machine for development and testing purposes.

Contribution

Feel free to fork the repository, create a feature branch, and submit a Pull Request.
