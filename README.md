# Context-X - Advanced React and Firebase Auth Starter

A modern, production-ready authentication starter built with **React**, **Vite**, **Firebase Authentication**, **Tailwind CSS**, and **DaisyUI**.  
Seamlessly manage user authentication, protected routes, and beautiful UI - all with best practices and extensibility in mind.

## Features

- **React 18** with [Vite](https://vitejs.dev/) for instant HMR and lightning-fast builds
- **Firebase Authentication** (Email/Password and Google OAuth)
- **Context API** for global auth state management
- **Protected Routes** with React Router v6
- **Tailwind CSS** and **DaisyUI** for rapid, responsive, and accessible UI development
- **TypeScript** for type safety and scalability
- **Reusable Components**: Header, Profile, Orders, Auth Forms
- **Customizable Themes** (light, dark, cupcake)
- **ESLint** and **Prettier** for code quality
- **Production-ready** structure and best practices

## Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/md-abu-kayser/context-x-auth-starter.git
```

```bash
cd context-x-auth-starter
```

2. **Install dependencies:**

```bash
npm install
# or
pnpm install
# or
yarn
```

3. **Run locally:**

```bash
npm run dev
# or
pnpm dev
```

## Authentication Flow

- **Register:** Create a new account with email and password.
- **Login:** Sign in with email/password or Google.
- **Protected Routes:** /profile and /orders are accessible only to authenticated users.
- **Profile Management:** View and (extend to) edit user profile.
- **Logout:** Securely sign out from any page.

## Theming and Styling

- Built with Tailwind CSS and DaisyUI for rapid, customizable UI.
- Switch between light, dark, and cupcake themes.
- Responsive and accessible by default.

## Scripts formatting

---

- npm run dev # Start development server
- npm run build # Build for production
- npm run preview # Preview production build
- npm run lint # Run ESLint
- npm run format # Run Prettier
- npm run type-check # Run TypeScript type checks

---

### Extending Functionality

- **Add Fire Store:** Connect orders or user data to Fire store.
- **Profile Editing:** Implement profile update logic in Profile.tsx.
- **Password Reset:** Add a password reset flow.
- **Role-based Access:** Extend AuthProvider for admin/user roles.

### Technologies Used

- React 18
- Vite
- Firebase Authentication
- Tailwind CSS
- DaisyUI
- TypeScript
- ESLint and Prettier

## License

This project is licensed under the terms of the **MIT License**.
The license may be modified for client or proprietary projects as required.

---

## Contact & Maintainer

**Md Abu Kayser** - Frontend / Full-Stack Web Developer

- **Project:** Context-X - context-x-auth-starter
- **GitHub:** https://github.com/md-abu-kayser
- **Email:** abu.kayser.official@gmail.com

---

**For collaboration, interviews, or client-related inquiries, feel free to reach out via GitHub or email.**

---
