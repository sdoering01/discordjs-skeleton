# discordjs-skeleton
Skeleton for discord.js bot applications

## Getting Started

Clone this repository and follow the steps:
* Initialise npm and install the required packages
```
npm init
npm install discord.js
npm install dotenv --save-dev
```
* In your `package.json` add `"start_local": "node -r dotenv/config server.js"` to your scripts
* Rename the `.env.example` file to `.env` and insert your bot token.
  Note that the `.env` file will not be checked into the repository with the default `.gitignore`.
* Start the application with `npm run start_local`
