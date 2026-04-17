# ☁️✨ Droply

Droply is your secure, personal cloud storage vault for effortlessly saving, organizing, and protecting all your favorite images and files. 

## 🌟 Features

* **Secure Login:** Safe and easy user authentication.
* **File Uploads:** Fast and secure image and file storage.
* **Organize Everything:** Create folders to keep your files neat and tidy.
* **Favorites:** "Star" your most important files to find them quickly.
* **Trash Bin:** Safely delete files and restore them if you make a mistake.
* **Beautiful Design:** Dark mode by default with a clean, modern interface.

## 🛠️ Built With

This project uses modern web development tools:
* **Framework:** [Next.js](https://nextjs.org/) (React)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Database:** [Neon Postgres](https://neon.tech/) & [Drizzle ORM](https://orm.drizzle.team/)
* **Authentication:** [Clerk](https://clerk.com/)
* **File Storage:** [ImageKit](https://imagekit.io/)
* **Deployment:** [Vercel](https://vercel.com/)

## 🚀 How to Run Locally

Want to run Droply on your own computer? Follow these simple steps:

### 1. Clone the repository
```bash
git clone [https://github.com/yourusername/droply.git](https://github.com/yourusername/droply.git)
cd droply
````

### 2\. Install dependencies

```bash
npm install
```

### 3\. Set up environment variables

Create a `.env.local` file in the root folder and add your secret API keys for Clerk, Neon Database, and ImageKit:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key_here
CLERK_SECRET_KEY=your_key_here
DATABASE_URL=your_neon_connection_string
# Add your ImageKit keys here as well
```

### 4\. Push the database schema

Set up your Neon database tables by running:

```bash
npx drizzle-kit push
```

### 5\. Start the app

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app!

## 🌍 Live Demo

Check out the live version of Droply here: https://droply-oll146i70-nitikas-projects.vercel.app
