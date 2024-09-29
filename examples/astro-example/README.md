# Astro Example

This is an example of how to use Better Auth with Astro. It uses Solid for building the components.


**Implements the following features:**
Email & Password . Social Sign-in with Google . Passkeys . Email Verification . Password Reset . Two Factor Authentication . Profile Update . Session Management


## How to run

1. Clone the code sandbox (or the repo) and open it in your code editor
2. Provide .env file with the following variables
   ```txt
   GOOGLE_CLIENT_ID=
   GOOGLE_CLIENT_SECRET=
   BETTER_AUTH_SECRET=
   ```
   //if you don't have these, you can get them from the google developer console. If you don't want to use google sign-in, you can remove the google config from the `auth.ts` file.

3. Run the following commands
   ```bash
   pnpm install
   pnpm run dev
   ```
4. Open the browser and navigate to `http://localhost:3000`