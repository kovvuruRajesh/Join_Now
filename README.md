<h1>Join Now</h1>

<p>This platform integrates secure authentication with Clerk, dynamic real-time meeting controls, and efficient scheduling for future and past meetings. It prioritizes user experience with a responsive design, ensuring seamless functionality across all devices. Key features include access to recorded meetings, personal meeting rooms, and detailed participant management for a comprehensive, user-friendly experience.</p>


**Cloning the Repository**

```bash
git clone https://github.com/kovvuruRajesh/Join_Now.git
cd zoom-clone
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```



```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

