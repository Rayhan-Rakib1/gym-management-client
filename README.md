 ██████╗ ██╗   ██╗███╗   ███╗    ███╗   ███╗ █████╗ ███╗   ██╗ █████╗  ██████╗ ███████╗███╗   ███╗███████╗███╗   ██╗████████╗
██╔════╝ ██║   ██║████╗ ████║    ████╗ ████║██╔══██╗████╗  ██║██╔══██╗██╔════╝ ██╔════╝████╗ ████║██╔════╝████╗  ██║╚══██╔══╝
██║  ███╗██║   ██║██╔████╔██║    ██╔████╔██║███████║██╔██╗ ██║███████║██║  ███╗█████╗  ██╔████╔██║█████╗  ██╔██╗ ██║   ██║   
██║   ██║██║   ██║██║╚██╔╝██║    ██║╚██╔╝██║██╔══██║██║╚██╗██║██╔══██║██║   ██║██╔══╝  ██║╚██╔╝██║██╔══╝  ██║╚██╗██║   ██║   
╚██████╔╝╚██████╔╝██║ ╚═╝ ██║    ██║ ╚═╝ ██║██║  ██║██║ ╚████║██║  ██║╚██████╔╝███████╗██║ ╚═╝ ██║███████╗██║ ╚████║   ██║   
 ╚═════╝  ╚═════╝ ╚═╝     ╚═╝    ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝     ╚═╝╚══════╝╚═╝  ╚═══╝   ╚═╝   

[![Next.js](https://img.shields.io/badge/Next.js-16.0.10-black?logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2.0-blue?logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.1.17-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A modern, full-featured gym management system built with Next.js, offering seamless membership management, payment processing, workout tracking, and comprehensive dashboards for members, trainers, and administrators.

## 🌐 Live Demo

**[https://gymflowgym.vercel.app](https://gymflowgym.vercel.app)**

---

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Available Scripts](#available-scripts)
- [User Roles & Dashboards](#user-roles--dashboards)
- [Payment Integration](#payment-integration)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

**GymFlow** is a comprehensive gym management platform designed to streamline operations for fitness centers. It provides role-based access control with dedicated dashboards for members, trainers, and administrators, enabling efficient management of memberships, payments, workout plans, attendance, and more.

### **Why GymFlow?**

- ✨ **Modern UI/UX** - Beautiful, responsive design built with Tailwind CSS & shadcn/ui
- 🔐 **Secure Authentication** - JWT-based authentication with role-based access control
- 💳 **Payment Integration** - SSLCommerz payment gateway for seamless online payments
- 📊 **Analytics Dashboard** - Real-time insights and data visualization
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- 🚀 **High Performance** - Built on Next.js 15 with App Router for optimal speed

---

## ✨ Key Features

### 🏠 **Public Features**

- **Landing Page** - Engaging hero banner with gym highlights
- **Membership Plans** - Browse and compare membership tiers
- **Trainer Profiles** - View trainer expertise and specializations
- **Class Schedule** - Explore available fitness classes
- **Contact & FAQ** - Get support and answers to common questions

### 👤 **Member Dashboard**

- **Membership Management**
  - View current membership status and expiry
  - Renew membership with multiple payment options
  - Access membership history
- **Payment Portal**
  - Online payment via SSLCommerz (Credit/Debit Card, bKash, Nagad)
  - Offline payment options (Cash, Card at counter)
  - Payment history with invoice downloads
  - Success/Fail/Cancel payment handling
- **Workout Plans**
  - Access personalized workout plans from trainers
  - Track workout progress
  - View exercise details and instructions
- **Class Bookings**
  - Browse available classes
  - Book and manage class reservations
- **Progress Tracking**
  - Monitor fitness goals and achievements
  - View workout statistics

### 🎓 **Trainer Dashboard**

- **Member Management**
  - View assigned members
  - Track member progress
- **Workout Plan Creation**
  - Create customized workout plans
  - Assign exercises with sets, reps, and duration
  - Manage and update existing plans
- **Class Management**
  - Schedule and manage fitness classes
  - View class attendance
- **Attendance Tracking**
  - Mark member attendance
  - View attendance reports

### 👨‍💼 **Admin Dashboard**

- **Payment Management**
  - View all transactions with advanced filters
  - Payment statistics (revenue, pending, overdue)
  - Download invoices
  - Process refunds
  - Manual payment entry
- **Member Management**
  - View and manage all members
  - Update member information
  - Manage membership status
- **Trainer Management**
  - Add and manage trainers
  - Assign members to trainers
  - View trainer performance
- **Plan Management**
  - Create and manage membership plans
  - Set pricing and discounts
  - Define plan features
- **Reports & Analytics**
  - Revenue reports
  - Membership analytics
  - Attendance statistics

---

## 🛠️ Technology Stack

### **Frontend**

| Technology                                    | Version | Purpose                         |
| --------------------------------------------- | ------- | ------------------------------- |
| [Next.js](https://nextjs.org/)                | 16.0.10  | React framework with App Router |
| [React](https://reactjs.org/)                 | 19.2.0  | UI library                      |
| [TypeScript](https://www.typescriptlang.org/) | 5.x     | Type-safe development           |
| [Tailwind CSS](https://tailwindcss.com/)      | 4.1.17  | Utility-first CSS framework     |
| [shadcn/ui](https://ui.shadcn.com/)           | Latest  | Reusable component library      |
| [Radix UI](https://www.radix-ui.com/)         | Latest  | Accessible UI primitives        |

### **State Management & Forms**

| Technology                                      | Purpose                       |
| ----------------------------------------------- | ----------------------------- |
| [React Hook Form](https://react-hook-form.com/) | Form handling with validation |
| [Zod](https://zod.dev/)                         | Schema validation             |
| [Sonner](https://sonner.emilkowal.ski/)         | Toast notifications           |

### **Data Visualization & Icons**

| Technology                          | Purpose              |
| ----------------------------------- | -------------------- |
| [Recharts](https://recharts.org/)   | Charts and analytics |
| [Lucide React](https://lucide.dev/) | Icon library         |

### **Authentication & Security**

| Technology   | Purpose                       |
| ------------ | ----------------------------- |
| JWT          | Token-based authentication    |
| js-cookie    | Client-side cookie management |
| jsonwebtoken | Token generation/validation   |

### **Payment Gateway**

| Technology                                | Purpose                         |
| ----------------------------------------- | ------------------------------- |
| [SSLCommerz](https://www.sslcommerz.com/) | Payment processing (Bangladesh) |

### **Deployment**

| Platform                      | Purpose                |
| ----------------------------- | ---------------------- |
| [Vercel](https://vercel.com/) | Hosting and deployment |

---

## 📁 Project Structure

```
gym-flow/
├── public/
│   └── Images/              # Static images and assets
├── src/
│   ├── app/                 # Next.js 15 App Router
│   │   ├── (Authentication)/    # Auth pages (signin, signup, etc.)
│   │   ├── (dashboardLayout)/   # Dashboard layouts
│   │   │   └── (commonDashboard)/
│   │   │       └── dashboard/
│   │   │           ├── admin/   # Admin dashboard pages
│   │   │           ├── member/  # Member dashboard pages
│   │   │           └── trainer/ # Trainer dashboard pages
│   │   ├── (publicLayout)/      # Public pages layout
│   │   ├── globals.css          # Global styles
│   │   └── layout.tsx           # Root layout
│   ├── components/
│   │   ├── modules/         # Feature-specific components
│   │   │   ├── Home/        # Homepage components
│   │   │   ├── dashboard/   # Dashboard components
│   │   │   ├── class/       # Class management
│   │   │   ├── member/      # Member components
│   │   │   ├── trainer/     # Trainer components
│   │   │   ├── Payment/     # Payment components
│   │   │   └── forms/       # Form components
│   │   ├── shared/          # Reusable shared components
│   │   │   ├── Navbar.tsx
│   │   │   ├── Footer.tsx
│   │   │   ├── Sidebar.tsx
│   │   │   └── DataTable.tsx
│   │   └── ui/              # shadcn/ui components
│   ├── hooks/               # Custom React hooks
│   │   ├── useAuth.ts
│   │   └── useTokenRefresh.ts
│   ├── lib/                 # Utility functions
│   │   ├── utils.ts
│   │   ├── jwtHandler.ts
│   │   ├── serverFetch.ts
│   │   └── navigation.config.ts
│   ├── services/            # API service layers
│   │   ├── auth/
│   │   ├── member/
│   │   ├── trainer/
│   │   ├── payment/
│   │   ├── plan/
│   │   ├── class/
│   │   ├── workout/
│   │   └── attendance/
│   ├── types/               # TypeScript type definitions
│   │   ├── user.types.ts
│   │   ├── member.types.ts
│   │   ├── trainer.types.ts
│   │   ├── payment.types.ts
│   │   └── plan.types.ts
│   └── zod/                 # Zod validation schemas
├── .env.local               # Environment variables (not in repo)
├── next.config.ts           # Next.js configuration
├── tailwind.config.ts       # Tailwind CSS configuration
├── tsconfig.json            # TypeScript configuration
└── package.json             # Dependencies and scripts
```

---

## 🚀 Getting Started

### **Prerequisites**

Ensure you have the following installed:

- **Node.js** >= 18.x
- **npm** or **yarn** or **pnpm**
- **Git**

### **Installation**

1. **Clone the repository**

   ```bash
   git clone https://github.com/abusaiyedjoy/Gym-Flow-Client.git
   cd gym-flow
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the root directory:

   ```env
   # API Configuration
   NEXT_PUBLIC_API_BASE_URL=http://localhost:5000/api

   # Authentication
   NEXT_PUBLIC_JWT_SECRET=your_jwt_secret_key_here

   # SSLCommerz Payment Gateway (Optional - for payment features)
   NEXT_PUBLIC_SSLCOMMERZ_STORE_ID=your_store_id
   NEXT_PUBLIC_SSLCOMMERZ_STORE_PASSWORD=your_store_password
   NEXT_PUBLIC_SSLCOMMERZ_IS_LIVE=false
   ```

4. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

5. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000)

---

## 🔧 Environment Variables

Create a `.env.local` file with the following variables:

| Variable                                | Description                         | Required             |
| --------------------------------------- | ----------------------------------- | -------------------- |
| `NEXT_PUBLIC_API_BASE_URL`              | Backend API base URL                | ✅ Yes               |
| `NEXT_PUBLIC_JWT_SECRET`                | JWT secret key for token encryption | ✅ Yes               |
| `NEXT_PUBLIC_SSLCOMMERZ_STORE_ID`       | SSLCommerz store ID (for payments)  | ⚠️ If using payments |
| `NEXT_PUBLIC_SSLCOMMERZ_STORE_PASSWORD` | SSLCommerz store password           | ⚠️ If using payments |
| `NEXT_PUBLIC_SSLCOMMERZ_IS_LIVE`        | SSLCommerz environment (true/false) | ⚠️ If using payments |

**Note:** Never commit `.env.local` to version control. Use `.env.example` for reference.

---

## 📜 Available Scripts

| Command         | Description                                         |
| --------------- | --------------------------------------------------- |
| `npm run dev`   | Start development server at `http://localhost:3000` |
| `npm run build` | Create production build                             |
| `npm run start` | Start production server                             |
| `npm run lint`  | Run ESLint for code quality checks                  |

---

## 👥 User Roles & Dashboards

### **1. Member**

**Access:** `/dashboard/member`

- View and manage membership
- Renew membership with payment
- Access workout plans
- Book classes
- Track progress
- View payment history

### **2. Trainer**

**Access:** `/dashboard/trainer`

- View assigned members
- Create and manage workout plans
- Schedule classes
- Track member attendance
- Monitor member progress

### **3. Admin**

**Access:** `/dashboard/admin`

- Manage all members and trainers
- Process payments and refunds
- Create membership plans
- View analytics and reports
- Manage system settings

---

## 💳 Payment Integration

GymFlow integrates with **SSLCommerz** payment gateway, supporting:

- ✅ **Credit/Debit Cards** (Visa, Mastercard, Amex)
- ✅ **Mobile Banking** (bKash, Nagad, Rocket)
- ✅ **Internet Banking**
- ✅ **Offline Payments** (Cash, Card at counter)

### **Payment Flow**

1. Member selects membership plan
2. Chooses payment method
3. Redirected to SSLCommerz gateway (for online payments)
4. Completes payment
5. SSLCommerz redirects back with transaction status
6. Invoice generated and sent via email
7. Payment history updated

### **Payment Features**

- 📄 **Invoice Generation** - Automatic PDF invoices
- 📧 **Email Notifications** - Payment confirmations
- 💰 **Refund Processing** - Easy refund management
- 📊 **Payment Analytics** - Revenue tracking and reports

---

## 🎨 UI Components

Built with **shadcn/ui** components:

- Buttons, Cards, Dialogs
- Forms, Inputs, Selects
- Tables, Tabs, Progress Bars
- Badges, Avatars, Accordions
- Radio Groups, Checkboxes
- Custom DataTable with sorting/filtering

---

## 🔐 Authentication Flow

1. **Registration** → User creates account (Member/Trainer)
2. **Email Verification** → OTP sent to email
3. **Login** → JWT tokens issued (access + refresh)
4. **Protected Routes** → Middleware validates tokens
5. **Token Refresh** → Automatic refresh before expiry
6. **Logout** → Tokens cleared

---

## 📱 Responsive Design

- **Mobile-First Approach** - Optimized for mobile devices
- **Breakpoints:**
  - `sm:` 640px (Mobile landscape)
  - `md:` 768px (Tablet)
  - `lg:` 1024px (Desktop)
  - `xl:` 1280px (Large desktop)
  - `2xl:` 1536px (Extra large)

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Rakibul Hasan**

- Email: rayhanrakib114@gmail.com
- GitHub: [@Rayhan-Rakib1](https://github.com/Rayhan-Rakib1)
- Repository: [Gym-Flow-Client](https://github.com/Rayhan-Rakib1/gym-management-client)

---

## 🙏 Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [shadcn/ui](https://ui.shadcn.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vercel](https://vercel.com/) for hosting
- [SSLCommerz](https://www.sslcommerz.com/) for payment integration

---

## 📞 Support

For support, email support@gymflow.com or open an issue on GitHub

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

Made with ❤️ by Rayhan Rakib

[Live Demo](https://gymflowgym.vercel.app) | [Report Bug](https://github.com/Rayhan-Rakib1/gym-management-client/issues) | [Request Feature](https://github.com/Rayhan-Rakib1/gym-management-client/issues)

</div>
