## Nhost & Next.js with custom backend url issue

### Installation

#### 1. First, clone this repo.

#### 2. Then, change the client and server url to:

```
  client_url: https://your-client-subdomain.ngrok.io
  server_url: https://your-server-subdomain.ngrok.io
```

#### 3. Run both frontend and backend

#### 4. Register new user with username/password method

#### 5. Open MailHog
Click on the confirmation link.

#### 6. See issue
The user email is not confirmed.

### Expect

The user email can be confirmed and will be redirected to https://your-client-subdomain.ngrok.io
