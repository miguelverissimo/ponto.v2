## Features

- DB access with Prisma
- Shadcn UI
- Folder structure

## Getting Started

- [ ] Install dependencies
  ```bash
  pnpm install
  ```
- [ ] Rename the app in `package.json` and `src/app/layout.tsx`
- [ ] Start the postgres container (if needed)
  ```bash
  pnpm start:db
  ```
- [ ] Set the database url in `.env`
- [ ] edit `prisma/schema.prisma` and add the models
- [ ] Generate the Prisma client
  ```bash
  pnpx prisma generate
  ```
- [ ] Add shadcn components to the project

  ```bash
  pnpm shadcn-ui@latest add
  ```

- [ ] Start the development server
  ```bash
  pnpm dev
  ```
