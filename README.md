# ==================================================================================================================================

## INITIAL

npx create-next-app@latest ./

npm install @headlessui/react cloudinary jsonwebtoken @types/jsonwebtoken graphql-request next-auth
npm install @grafbase/sdk --save-dev

remove all from app
create a file called page.tsx and add the below
rfce
npm run dev

# ==================================================================================================================================

## Some Important Files

Layout.tsx
common.types.ts
constants folder (used in navbar.tsx)
AuthProviders (used in navbar.tsx)
grafbase.config.ts
route.ts, session.ts
lib folder
graphql folder (https://youtu.be/986hztrfaSQ?si=ZK9LzyCs2cZja9cQ&t=4651)

# ==================================================================================================================================

## External Integrations

## 00:36:22 - Grafbase : https://www.youtube.com/watch?v=986hztrfaSQ&t=2182s

    NEXT_PUBLIC_GRAFBASE_API_URL, NEXT_PUBLIC_GRAFBASE_API_KEY https://youtu.be/986hztrfaSQ?si=0f2ioJ9nloTQI5vh&t=2701


    npm grafbase init -config-format typescript
    grafbase.config.ts
    Define Data Models
    -- https://grafbase.com/docs/database
    // Integrate Auth
    // https://grafbase.com/docs/auth ½/-const authProvider = auth.OpenIDConnect({
    //• • issuer: process. env. ISSUER_URL * ??
    // })
    //

## 00:46:33 - Authentication (NextAuth)

    https://www.youtube.com/watch?v=986hztrfaSQ&t=2793s
    https://next-auth.js.org/getting-started/example
    AuthProviders.tsx
    route.ts, session.tsx    https://youtu.be/986hztrfaSQ?si=ct-BQlCIArW4MLgV&t=3145
    GOOGLE_CLIENT_ID,GOOGLE_CLIENT_SECRET : https://youtu.be/986hztrfaSQ?si=2NO-X_6E7KyjFdWM&t=3617
    NEXTAUTH_SECRET, NEXTAUTH_URL:
        https://youtu.be/986hztrfaSQ?si=bAHk-fStrsq5XAAV&t=5407
        To generate Secret with openSSL run this  : openssl rand -base64 32  (or https://www.cryptool.org/en/cto/openssl and enter openssl rand -base64 32)

## cloudinary https://youtu.be/986hztrfaSQ?si=Tk-5n_9slRPxRSFg&t=9400

    CLOUDINARY_NAME, CLOUDINARY_KEY, CLOUDINARY_SECRET

# ==================================================================================================================================

# DEPLOYMENT https://youtu.be/986hztrfaSQ?si=WpZiCdtyYitB9-31

    NEXT_PUBLIC_SERVER_URL
    NEXT_PUBLIC_GRAFBASE_API_URL, NEXT_PUBLIC_GRAFBASE_API_KEY
    GOOGLE_CLIENT_ID,GOOGLE_CLIENT_SECRET
    NEXTAUTH_SECRET (This should ne set in vercel and graphbase env), NEXTAUTH_URL
    CLOUDINARY_NAME, CLOUDINARY_KEY, CLOUDINARY_SECRET

# ==================================================================================================================================

# Build and Deploy a Full Stack Next.js 13 Application | React, Next JS 13, TypeScript, Tailwind CSS

![Flexibble](https://i.ibb.co/CvSk76H/Thumbnail.png)

## Introduction

Next.js has the potential to revolutionize the industry and forever change the way we develop web applications. You’re still early in catching the trend and building your own Next.js 13 applications with TypeScript that leverage features such as server-side rendering and the app router.

In this video, you'll learn:
Alongside building this application, you'll also learn how to:

- Use Next.js 13 App Router and Server side Rendering
- Implement Filtering Functionality
- Complete Pagination Capabilities
- Handle image uploads
- Understanding and writing proper TypeScript
- Learn Grafbase - a serverless GraphQL platform

## Want to land your dream programming job in 3 - 6 months?

⭐ JSM Masterclass Experience - https://jsmastery.pro/masterclass
Become a Software Engineer. Guaranteed.
