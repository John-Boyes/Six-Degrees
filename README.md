## Six Degrees Game
The game will load two random actors who have not been in the same movie. The player enters the names of up to five actors to connect the two starting actors to each other. This game uses MySQL databases to populate the random actors and cache game data. TMDB API is used to compare movies from starting actors and user inputed actors when validating answers.

### Game Description

The goal is to connect the actors in under six degrees of separation. The first degree must be an actor who was on screen with Actor 1, and if they were on screen with both actors you win the game.

Each subsequent degree you use must connect to the previous degree, and the game ends when current degree also connects to actor 2.

Example:
Actor 1 > First Degree > Actor 2

Example:
Actor 1 > First Degree > Second Degree > Actor 2



## Learn More About This Stack
This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!


Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
