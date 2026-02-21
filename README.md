# please consult the license 

project fujo is NOW fully functional!

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


ahem ahem ought to shut this down too

<img width="488" height="76" alt="image" src="https://github.com/user-attachments/assets/f9859060-643a-460d-b969-b9e829a5693f" />
