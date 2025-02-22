# AI language learning assistant

Make sure Git and NodeJS is installed.
all Project Dependencies using npm install --legacy-peer-deps or yarn install --legacy-peer-deps.

Run the Seed Script:

In the same terminal, run the following command to execute the seed script:

npm run db:push && npm run db:prod
This command uses npm to execute the Typescript file (scripts/prod.ts) and writes challenges data in database.

Verify Data in Database:
Once the script completes, check your database to ensure that the challenges data has been successfully seeded.

Now app is fully configured 👍 and you can start using this app using either one of npm run dev
