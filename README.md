# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npx sv create

# create a new project in my-app
npx sv create my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.


TELEPÍTENDŐ

 Z:\Szeged_Programfejlesztes_Suli\Frontend\2025_02_15\SAJAT> npx sv create
Need to install the following packages:
sv@0.6.21
Ok to proceed? (y) y

┌  Welcome to the Svelte CLI! (v0.6.21)
│
◇  Where would you like your project to be created?
│  ./
│
◇  Which template would you like?
│  SvelteKit minimal
│
◇  Add type checking with Typescript?
│  No
│
◆  Project created
│
◇  What would you like to add to your project? (use arrow keys / space bar)
│  drizzle, lucia
│
◇  lucia: Do you want to include a demo? (includes a login/register page)
│  Yes
│
◇  drizzle: Which database would you like to use?
│  SQLite
│
◇  drizzle: Which SQLite client would you like to use?
│  better-sqlite3
│
◆  Successfully setup add-ons
│
◇  Which package manager do you want to install dependencies with?
│  npm
│
◆  Successfully installed dependencies
│
◇  Project next steps ─────────────────────────────────────────────────────╮
│                                                                          │
│  1: git init && git add -A && git commit -m "Initial commit" (optional)  │
│  2: npm run dev -- --open                                                │
│                                                                          │
│  To close the dev server, hit Ctrl-C                                     │
│                                                                          │
│  Stuck? Visit us at https://svelte.dev/chat                              │
│                                                                          │
├──────────────────────────────────────────────────────────────────────────╯
│
◇  Add-on next steps ──────────────────────────────────────────────────╮
│                                                                      │
│  lucia:                                                              │
│  - Run npm run db:push to update your database schema                │
│  - Visit /demo/lucia route to view the demo                          │
│                                                                      │
│  drizzle:                                                            │
│  - You will need to set DATABASE_URL in your production environment  │
│  - Run npm run db:push to update your database schema                │
│                                                                      │
├──────────────────────────────────────────────────────────────────────╯
│
└  You're all set!

PS Z:\Szeged_Programfejlesztes_Suli\Frontend\2025_02_15\SAJAT> ls


    Directory: Z:\Szeged_Programfejlesztes_Suli\Frontend\2025_02_15\SAJAT