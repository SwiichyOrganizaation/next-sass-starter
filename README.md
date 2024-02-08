# Next Auth v5 - Advanced Guide (2024)

![image](https://github.com/AntonioErdeljac/next-auth-v5-advanced-guide/assets/23248726/d0175397-8c3f-4e82-91c4-78c14f29bb81)

This is a repository for Next Auth v5 - Advanced Guide (2024)

[VIDEO TUTORIAL](https://youtu.be/1MTyCvS05V4)

Key Features:

- 🔐 Next-auth v5 (Auth.js)
- 🚀 Next.js 14 with server actions
- 🔑 Credentials Provider
- 🌐 OAuth Provider (Social login with Google & GitHub)
- 🔒 Forgot password functionality
- ✉️ Email verification
- 📱 Two factor verification
- 👥 User roles (Admin & User)
- 🔓 Login component (Opens in redirect or modal)
- 📝 Register component
- 🤔 Forgot password component
- ✅ Verification component
- ⚠️ Error component
- 🔘 Login button
- 🚪 Logout button
- 🚧 Role Gate
- 🔍 Exploring next.js middleware
- 📈 Extending & Exploring next-auth session
- 🔄 Exploring next-auth callbacks
- 👤 useCurrentUser hook
- 🛂 useRole hook
- 🧑 currentUser utility
- 👮 currentRole utility
- 🖥️ Example with server component
- 💻 Example with client component
- 👑 Render content for admins using RoleGate component
- 🛡️ Protect API Routes for admins only
- 🔐 Protect Server Actions for admins only
- 📧 Change email with new verification in Settings page
- 🔑 Change password with old password confirmation in Settings page
- 🔔 Enable/disable two-factor auth in Settings page
- 🔄 Change user role in Settings page (for development purposes only)

### Prerequisites

**Node version 18.7.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next-auth-v5-advanced-guide.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
DATABASE_URL=
DIRECT_URL=

AUTH_SECRET=

GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

RESEND_API_KEY=

NEXT_PUBLIC_APP_URL=
```

### Setup Prisma

```shell
npx prisma generate
npx prisma db push
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |

DATABASE_URL=postgresql://postgres:F*3Dg-Fd*Fgbda242GgaFEGA14CEbCaB@monorail.proxy.rlwy.net:56354/railway
DIRECT_URL=postgresql://postgres:F*3Dg-Fd*Fgbda242GgaFEGA14CEbCaB@monorail.proxy.rlwy.net:56354/railway

AUTH_SECRET=WwKNWtivoQymrqvbiJjnFUdofxYa0a+Aiwp+qvwIXg8=

GITHUB_CLIENT_ID=b813c25a60364f64c27d
GITHUB_CLIENT_SECRET=4c1aecf2f8e8350958172ba4a6f49643c6a89677

GOOGLE_CLIENT_ID=975226416002-2jeno9gk6lr38louql2dbustspoet3q6.apps.googleusercontent.com
GOOGLE_CLIENT_SECRET=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

RESEND_API_KEY=re_LuTyJEqy_KjwCSosmGv5XwvtYDmRVncwt

NEXT_PUBLIC_APP_URL=http://localhost:3000
