# WorkPilot

WorkPilot is a role-based project and team management system designed to help organizations manage projects, members, announcements, and approvals with a structured workflow. It includes dashboards for Admins, Team Leads, and Members with dedicated permissions and tools.

---

## 🚀 Features

### 🔹 Project Management

* Create, manage, and view all projects
* Project cards display:

  * Title, Description, Domain
  * Status (Active / Completed / Disabled)
  * Team Lead & Assistant Lead
  * Member Count
* Members can apply to open projects
* Admin approves project proposals

### 🔹 Announcements System

* Create, edit, pin, delete announcements
* Announcements grouped by month
* Shows sender profile, content, timestamp
* Members can only view announcements

### 🔹 Members & Team Management

* Member cards show: profile, name, GitHub, LinkedIn
* Admin manages domain-wide members
* Team Leads manage project members
* Members view only projects they are part of

### 🔹 Requests & Approvals

* Members apply to open projects
* Leads approve/reject member requests
* Admin approves project proposals
* Status tracking: In Consideration / Approved / Rejected

---

## 👥 Role-Based Access Overview

| Feature                      | Admin | Team Lead | Member |
| ---------------------------- | ----- | --------- | ------ |
| View All Projects            | ✔️    | ✔️        | ✔️     |
| Apply to Projects            | ❌     | ❌         | ✔️     |
| Approve Project Applications | ✔️    | ❌         | ❌      |
| Submit New Projects          | ❌     | ✔️        | ✔️     |
| Add/Remove Project Members   | ✔️    | ✔️        | ❌      |
| Add/Remove Domain Members    | ✔️    | ✔️        | ❌      |
| Post Announcements           | ✔️    | ✔️        | ❌      |
| View Announcements           | ✔️    | ✔️        | ✔️     |

---

## 🧭 Dashboards

### 1️⃣ Admin Dashboard

* Approve/reject project proposals
* Publish final project cards
* Manage all members
* Create/manage announcements
* View pending member requests
* View all leads and members

**Sidebar includes:** All Projects, Create Announcement, All Leads, All Members, Pending Requests

---

### 2️⃣ Team Lead Dashboard

* Submit project proposals
* Approve/reject member applications
* Add/remove project members
* Toggle project availability
* View announcements

**Sidebar includes:** View All Projects, Pending Requests, My Projects, Project Members, Create Announcement

---

### 3️⃣ Member Dashboard

* Browse all projects
* Apply to open projects
* Track application status
* Submit new project proposals
* View announcements

**Sidebar includes:** All Projects, My Projects, Notifications

---

## 🏗️ Tech Stack

* Frontend: React / Vite / Tailwind
* Backend: Node.js / Express
* Database: MongoDB / PostgreSQL / MySQL
* Auth: JWT / Session
* Deployment: Render / Vercel

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/Archi-shaw/WorkPilot.git
cd WorkPilot
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create `.env` file:

```
PORT=4000
DATABASE_URL=
JWT_SECRET=
```

### Run Locally

```bash
npm run dev
```

### Build

```bash
npm run build
npm start
```

---

## 📣 Contributing

1. Fork the repo
2. Create a new branch
3. Commit changes
4. Open a PR

---

## 📜 License

MIT License
