<h1 align="center">🦷 Dentwise – Dental Platform with AI Voice Agent 🦷</h1>

![Demo App](/public/screenshot-for-readme.png)

Highlights:

- 🏠 Modern Landing Page with gradients & images
- 🔐 Authentication via Clerk (Google, GitHub, Email & Password)
- 🔑 Email Verification (6-digit code)
- 📅 Appointment Booking System
- 🦷 3-Step Booking Flow (Dentist → Service & Time → Confirm)
- 📩 Email Notifications for Bookings (Resend)
- 📊 Admin Dashboard for Managing Appointments
- 🗣️ AI Voice Agent powered by Vapi (Pro Plans only)
- 💳 Subscription Payments with Clerk (Free + 2 Paid Plans)
- 🧾 Automatic Invoices via Email
- 💸 Smart Subscription Upgrades (pay only the difference)
- 📂 PostgreSQL for Data Persistence
- 🎨 Styling with Tailwind CSS + Shadcn
- ⚡ Data Fetching with TanStack Query
- 🤖 CodeRabbit for PR Optimizations
- 🧑‍💻 Git & GitHub Workflow (branches, PRs, merges)
- 🚀 Deployment on Sevalla (free-tier friendly)

---

<h1>🦷 DentWise – Smart Dental Appointment & Management System</h1>

<p>
  <strong>DentWise</strong> is a modern full-stack web application designed to simplify
  <strong>dental clinic management</strong>. It allows patients to book appointments online
  while helping dentists manage users and schedules efficiently.
</p>

<p>
  Built using <strong>Next.js App Router</strong>, <strong>Prisma ORM</strong>,
  and <strong>Clerk Authentication</strong>.
</p>

<p>
  <img src="https://img.shields.io/badge/Next.js-15-black" />
  <img src="https://img.shields.io/badge/Prisma-ORM-blue" />
  <img src="https://img.shields.io/badge/PostgreSQL-DB-336791" />
  <img src="https://img.shields.io/badge/Auth-Clerk-purple" />
</p>

<hr />

<h2>🚀 Features</h2>

<h3>👤 Authentication & Authorization</h3>
<ul>
  <li>Secure authentication with Clerk</li>
  <li>Server-side protected actions</li>
  <li>Unique user mapping using Clerk ID</li>
</ul>

<h3>📅 Appointment Management</h3>
<ul>
  <li>Online dental appointment booking</li>
  <li>Authenticated access only</li>
  <li>Dashboard-based management</li>
</ul>

<h3>🖥️ Dashboard</h3>
<ul>
  <li>Admin dashboard for managing data</li>
  <li>View users and appointments</li>
  <li>Built with Next.js Server Actions</li>
</ul>

<hr />

<h2>🛠️ Tech Stack</h2>

<ul>
  <li><strong>Frontend:</strong> Next.js 15, TypeScript, Tailwind CSS</li>
  <li><strong>Backend:</strong> Prisma ORM</li>
  <li><strong>Database:</strong> PostgreSQL (Neon compatible)</li>
  <li><strong>Authentication:</strong> Clerk</li>
</ul>

<hr />

<h2>📂 Project Structure</h2>

<pre>
dentwise-master/
│
├── prisma/
│   └── schema.prisma
│
├── src/
│   ├── app/
│   ├── lib/
│   │   ├── prisma.ts
│   │   └── actions/
│   ├── components/
│   └── middleware.ts
│
├── .env
├── package.json
└── README.md
</pre>

<hr />

<h2>⚙️ Environment Variables</h2>

<pre>
DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_secret
</pre>

<hr />

<h2>🧑‍💻 Setup & Installation</h2>

<pre>
git clone https://github.com/DipanshuAmrate/dentwise-master.git
cd dentwise-master
npm install
npx prisma generate
npx prisma migrate dev
npm run dev
</pre>

<p>
  App runs at: <strong>http://localhost:3000</strong>
</p>

<hr />

<h2>🧪 Prisma Studio</h2>

<pre>
npx prisma studio
</pre>

<hr />

<h2>📈 Future Improvements</h2>
<ul>
  <li>Appointment approval workflow</li>
  <li>Email notifications</li>
  <li>Dentist profile management</li>
  <li>Analytics dashboard</li>
  <li>Payment integration</li>
</ul>

<hr />

<h2>👨‍💻 Author</h2>

<p>
  <strong>Dipanshu Amrate</strong><br />
  3rd Year Student | Web Developer | Full-Stack Enthusiast
</p>

<p>
  🔗 GitHub:
  <a href="https://github.com/DipanshuAmrate">
    https://github.com/DipanshuAmrate
  </a>
</p>

<p>⭐ Star the repository if you like this project!</p>



## 🧪 .env Setup

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

DATABASE_URL=your_postgres_database_url

NEXT_PUBLIC_VAPI_ASSISTANT_ID=your_vapi_assistant_id
NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key

ADMIN_EMAIL=your_admin_email

RESEND_API_KEY=your_resend_api_key

NEXT_PUBLIC_APP_URL=your_app_url

```

## Run the app

```bash
1- npm install
2- npm run dev
```
# dentwise-
