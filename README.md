# RAF Signature Events (Static)

This repository contains the static site for **RAF Signature Events**, including a public landing page and an admin dashboard. The site connects to Supabase for storing events and gallery images.

- **index.html** – Public site displaying upcoming events and gallery images.
- **admin.html** – Admin dashboard with login via Supabase Auth to manage events and upload cover images.

## Configuration

Before deploying, edit both HTML files and set your Supabase details:

```js
const SUPABASE_URL  = "https://pojudmrkqruuxklwvkvj.supabase.co";
const SUPABASE_ANON = "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InBvanVkbXJrcXJ1dXhrbHd2a3ZqIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NTYxMTE3ODgsImV4cCI6MjA3MTY4Nzc4OH0.dAwlj7yQm1eMz4weKroUC2t5Y_1N5koEHSpqqoH65G0";
```

Deploy using Vercel or any static hosting. See instructions in the project documentation.
