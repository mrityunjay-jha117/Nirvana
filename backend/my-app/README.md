# 1. Install all dependencies
npm install

# 2. Generate the Prisma client without bundling the engine
npx prisma generate --no-engine

# 3. Start the development server
npm run dev

# 4. to deploy
npm run deploy
