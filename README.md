# 📊 Kaiser Finance Web

> A modern, full-stack personal finance tracking application built for speed, security, and exceptional user experience.

---

## 🚀 Tech Stack

* **Framework:** [Next.js](https://nextjs.org/) (App Router, Server Actions)
* **Language:** [TypeScript](https://www.typescript.org/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **UI Components:** [Shadcn UI](https://ui.shadcn.com/) & [Radix UI](https://www.radix-ui.com/)
* **Database & Auth:** [Supabase](https://supabase.com/)
* **Icons:** [Lucide React](https://lucide.dev/)

---

## ✨ Features (In Progress)

- [ ] **Authentication:** Secure user sign-up, login, and session management via Supabase Auth.
- [ ] **Dashboard:** Visual overview of income, expenses, and total balance.
- [ ] **Transaction Management:** Full CRUD capabilities for tracking daily financial activities.
- [ ] **Category Customization:** Organize transactions with custom categories.
- [ ] **Responsive Design:** Seamless experience across desktop and mobile devices.

---

## 🛠️ Architecture & Structure

The project follows a modular, layer-based architecture using Next.js App Router and Server Actions:

```text
src/
├── actions/        # Server actions for business logic & database mutations
├── app/            # Next.js App Router routes and page layouts
├── components/     # Reusable UI components (Shadcn + custom elements)
├── config/         # Global application configuration
├── constants/      # App-wide constant definitions
├── lib/            # External service clients (Supabase setup)
└── types/          # TypeScript interfaces and type declarations
```

---

## ⚙️ Getting Started

### Prerequisites

* Node.js 18+ 
* npm, pnpm, or yarn

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/henrique-fullstack/kaiser-finance-web.git
   cd kaiser-finance-web
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Variables:**
   Create a `.env.local` file in the root directory and add your Supabase credentials:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).