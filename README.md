# Full Stack E-Commerce App with Next.js 15

## Overview
This project is a Full Stack E-Commerce application built using the latest **Next.js 15** framework. It leverages powerful tools like **Sanity**, **Stripe**, **Clerk**, **Tailwind CSS**, and **TypeScript** to create a scalable, real-time, and user-friendly platform. The application includes advanced features such as user authentication, live content updates, payment processing, state management, and sleek animations.

---

## Features

- **Sanity Integration**: A robust CMS to manage and scale app content effortlessly.
- **Sanity Live Content API**: Enables real-time customization and live updates.
- **Stripe Payments**: Seamless integration for order payments with a complete checkout flow.
- **Clerk Authentication**: User authentication with ease, including modern Passkeys.
- **Frontend UI/UX**: Designed with **Shadcn** and **Tailwind CSS** for a beautiful and responsive interface.
- **Framer Motion Animations**: Sleek animations to enhance user experience.
- **TypeScript**: Ensures type safety, reducing bugs and errors.
- **Vercel Deployment**: Easily deploy the production-ready application.
- **State Management**: Implemented using **Zustand** for global state handling.
- **Real-Time Visual Editor**: Powered by Sanity for instant content updates.
- **Caching and Performance**: Optimized with efficient caching mechanisms.

---

## Prerequisites

- **Node.js** (v16 or higher)
- **npm** or **yarn**
- **Git**
- Accounts for:
  - [Sanity](https://www.sanity.io/sonny)
  - [Clerk](https://go.clerk.com/k0ls6Zb)
  - [Stripe](https://stripe.com)

---

## Tech Stack

- **Frontend**: Next.js 15, Tailwind CSS, Shadcn, TypeScript
- **Backend**: Sanity CMS, Node.js
- **Payments**: Stripe
- **Authentication**: Clerk
- **Animations**: Framer Motion
- **State Management**: Zustand
- **Hosting**: Vercel

---

## Installation

1. Clone the repository:
   ```bash
   git clone <REPOSITORY_URL>
   cd ecommerce-app-sanity-next-15
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   - Create a `.env.local` file in the root directory.
   - Add the required API keys and configurations for Sanity, Clerk, and Stripe.

4. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

---

## Deployment

1. Build the production version:
   ```bash
   npm run build
   # or
   yarn build
   ```

2. Deploy to Vercel:
   ```bash
   npm run deploy
   ```

---

## Features Breakdown

### **Core Functionalities**
1. **Authentication**:
   - User login and signup with Clerk.
   - Passkey functionality for seamless authentication.

2. **Content Management**:
   - Real-time content updates via Sanity’s Live Content API.

3. **Product Management**:
   - Product schema using Sanity TypeGen.
   - Filtering, searching, and categorizing products.

4. **Checkout and Payments**:
   - Stripe integration for secure payment processing.
   - Custom webhooks for order updates.

5. **Animations and UI**:
   - Framer Motion for interactive animations.
   - Tailwind CSS for responsive design.

6. **State Management**:
   - Zustand for managing global states like basket items.

7. **Deployment**:
   - Hosting on Vercel for fast and reliable delivery.

---

## Resources

- [Sanity Documentation](https://www.sanity.io/docs)
- [Clerk Documentation](https://clerk.dev/docs)
- [Stripe Documentation](https://stripe.com/docs)
- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Framer Motion Documentation](https://www.framer.com/motion/)
- [Zustand Documentation](https://docs.pmnd.rs/zustand)

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
