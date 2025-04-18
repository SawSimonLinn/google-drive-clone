<div align="center">
  <br />
    <a href="https://www.sawlinn.com" target="_blank">
      <img src="https://i.ibb.co/wR9G2k3/Readme-Thumbnail.png" alt="Project Banner">
    </a>
  <br />

  <div>
     <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
  </div>

</div>

# Storage Management Solution

A web-based storage management solution built with **Next.js**, **TailwindCSS**, and **Appwrite**. This application allows users to manage files, view usage summaries, and sort files by type.

## Features

- **File Management**: Upload, view, and manage files.
- **Usage Summary**: Displays storage usage by file type (Documents, Images, Media, Others).
- **Sorting**: Sort files by name, size, or date.
- **Responsive Design**: Built with TailwindCSS for a modern and responsive UI.
- **Appwrite Integration**: Uses Appwrite for backend services.

## Tech Stack

- **Frontend**: React, Next.js, TailwindCSS
- **Backend**: Appwrite
- **Icons & Assets**: Custom SVG icons for file types

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SawSimonLinn/google-drive-clone.git
   cd google-drive-clone
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up enviroment variables:
   Create a `.env.local` file in the root directiory and add the following:

   ```bash
   NEXT_PUBLIC_APPWRITE_ENDPOINT=<your-appwrite-endpoint>
   NEXT_PUBLIC_APPWRITE_PROJECT=<your-appwrite-project-id>
   NEXT_PUBLIC_APPWRITE_DATABASES=<your-appwrite-bucket-id>
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=<your-appwrite-bucket-id>
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=<your-appwrite-bucket-id>
   NEXT_PUBLIC_APPWRITE_BUCKET=<your-appwrite-bucket-id>
   NEXT_APPWRITE_KEY=<your-appwrite-bucket-id>
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

   Open http://localhost:3000 in your browser.

## Deployment

This project is deployed using Vercel. You can access the live application at: [Live Deployment Link](https://google-drive-clone-lovat.vercel.app/sign-in)

**To deploy your own version**

1.  Push your code to a GitHub repository.
2.  Go to [Vercel](https://www.vercel.co) and import your repository.
3.  Set up the environment variables in the Vercel dashboard.
4.  Deploy the project with a single click.

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the application for production.
- `npm run start`: Start the production server.

## Customization

**TailwindCSS**
The project uses a custom TailwindCSS configuration. You can modify the theme in `tailwind.config.ts` to adjust colors, fonts, and other styles.

**Environment Variables**
Ensure you configure the `.env.local` file with your Appwrite project details.

**Contributing**
Contributions are welcome! Please fork the repository and submit a pull request.

**Acknowledgments**

- Next.js
- Tailwindcss
- Appwrite
