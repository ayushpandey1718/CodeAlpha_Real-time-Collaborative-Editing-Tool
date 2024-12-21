## Collaborative Editor

<p>
Built a Full-Stack Collaborative Editor using TypeScript and Next JS, which enabled a collaborative text editor with real-time updates, document management (including create, delete, share, and list operations), comments with threading, active collaborator indicators, and responsive design across all devices.
</p>

## [Collaborative Editor](https://collaborative-editor-ce.vercel.app)

### Features

- Authentication: User authentication using Google through NextAuth, ensuring secure sign-in/out and session management

- Collaborative Text Editor: Multiple users can edit the same document simultaneously with real-time updates

- Documents Management: CRDU operations (Create, Delete, Share, List)

  - **Create Documents**: Users can create new documents, which are automatically saved and listed.
  - **Delete Documents**: Users can delete documents they own.
  - **Share Documents**: Users can share documents via email or link with view/edit permissions.
  - **List Documents**: Display all documents owned or shared with the user, with search and sorting functionalities.

- Comments: Users can add inline and general comments, with threading for discussions

- Active Collaborators on Text Editor: Show active collaborators with real-time presence indicators

- Notifications: Notify users of document shares, new comments, and collaborator activities

- Responsive: The application is responsive across all devices

<br />

## Technical Skills 💻

<img align="left" alt="React/React Native" height="50px" src="https://cdn.svgporn.com/logos/react.svg" />
<img align="left" alt="Typescript" height="50px" src="https://cdn.svgporn.com/logos/typescript-icon.svg" />
<img align="left" alt="NextJS" height="50px" src="https://cdn.svgporn.com/logos/nextjs-icon.svg" />
<img align="left" alt="tailwindcss" height="50px" src="https://cdn.svgporn.com/logos/tailwindcss-icon.svg" />
<img align="left" alt="ShadCN" height="50px" src="https://avatars.githubusercontent.com/u/139895814?s=280&v=4" />
<img align="left" alt="Liveblocks" height="50px" src="https://pbs.twimg.com/profile_images/1623982338630733826/_dFRCa3T_400x400.png" />
<img align="left" alt="Lexical Editor" height="50px" src="https://seeklogo.com/images/L/lexical-icon-logo-270F9AECD6-seeklogo.com.png" />
<img align="left" alt="Clerk" height="50px" src="https://uploads.productlane.com/7254258eb34a7b4626b86f0fbd4c1ed6.png" />
<img align="left" alt="Git" height="50px" src="https://cdn.svgporn.com/logos/git-icon.svg" />
<img align="left" alt="Vercel" height="50px" src="https://cdn.svgporn.com/logos/vercel-icon.svg" />

<br />
<br />
<br />
<br />

## Getting Started

### Installation

<details>
1. Open Terminal.

2. Change the current working directory to the location where you want the cloned directory.

3. Clone the repository: `git clone https://github.com/jhwa426/Collaborative-Editor`
  
4. Navigate to the project directory: `cd collaborative-editor`

5. Install the dependencies: `npm install`

6. Set Up Environment Variables

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

7. Open your browser and visit: `http://localhost:3000`
</details>
