# Context-X - Advanced React and Firebase Auth Starter

<!-- Linting & Formatting -->

[![ESLint](https://img.shields.io/badge/ESLint-4B32C3?logo=eslint&logoColor=white)](https://eslint.org/docs/latest/)
[![Prettier](https://img.shields.io/badge/Prettier-2B3A42?logo=prettier&logoColor=white)](https://prettier.io/docs/)

<!-- Styling / PostCSS -->

[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/docs/)
[![PostCSS](https://img.shields.io/badge/PostCSS-efefef?logo=postcss&logoColor=black)](https://postcss.org/)

<!-- Bundler / Dev tooling -->

[![Vite](https://img.shields.io/badge/Vite-646cff?logo=vite&logoColor=white)](https://vite.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)](https://nodejs.org/)

<!-- Language -->

[![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/docs/)

<!-- Plain links (if you prefer link list) -->

- ESLint docs: https://eslint.org/docs/latest/
- Prettier docs: https://prettier.io/docs/
- Tailwind CSS docs: https://tailwindcss.com/docs/
- PostCSS docs / postcss.config: https://postcss.org/ (see also Tailwind PostCSS install guide)
- Vite docs: https://vite.dev/
- Node.js docs: https://nodejs.org/
- TypeScript docs: https://www.typescriptlang.org/docs/

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
