# Twitch-Clone-Next14-Prisma-MySql

## Getting Started

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next14-twitch-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
CLERK_WEBHOOK_SECRET=

DATABASE_URL=

LIVEKIT_API_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_WS_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Acknowledgment

This project drew inspiration or guidance from the YouTube video [Link to Video P1](https://www.youtube.com/watch?v=a02JAryRPVU) / [Link to Video P2](https://www.youtube.com/watch?v=nav55-4ISg4). Special thanks to the creator for their valuable insights.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.