# this project is NOT complete; there is currently no proper frontend, but the sheet and all backend functions function !!

# project-fujo
an frc analytics platform!
project FUJO (short for **F**eedback-Driven **U**ser **J**udgement & **O**bservation) is a fully cloud hosted FRC prediction system
users get points which they can use to place predictions on matches and get payouts; it features a leaderboard and can be integrated with other tools to give points more value


**(very) brief technical overview**
- load users and matches via a cloudflare serverless function which interacts with a google app scripts API layer
- place predictions on match outcomes with stake validation
- compute live odds and payouts based on predictions
- track user balances and updates from scouting activity

tech stack
- frontend: react, typescript, tailwind, vite, shadcn/ui / Radix UI primitives, framer motion, TanStack Query, charts.js, visx
- backend: cloudflare workers and google appscripts
- database: google sheets

