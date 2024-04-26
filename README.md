
Mirrow is a Full-stack Miro Clone project built by using Next JS 14, React, TypeScript, Shadcn UI, Tailwind CSS, Convex Database, Zustand, liveblocks, and Clerk Auth.

## Features

- Create organizations and invite team members seamlessly.
- Collaborate with team members seamlessly in Miro-like whiteboard interface.
- Real-time collaboration using the real-time Convex database.
- User authentication, organization creation, and management with Clerk Auth.
- Responsive design with TailwindCSS.
- State management using Zustand.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

1. **Clone the repository:**

```bash
git clone https://github.com/evanch98/notion-clone-nextjs.git
cd your-repo-name
```

2. **Install the required dependencies:**

```bash
npm install
```

3. **Configure environmental variables:**
   Create a `.env.local` file in the project root and set the necessary environment variables.

```
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
LIVEBLOCKS_SECRET_KEY=
```

4. **Run the development server:**

```bash
npm run dev
```

5. **Start building and customizing your Miro Clone!**
