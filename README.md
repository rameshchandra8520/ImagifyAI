# ImagifyAI

**Transform Your Images with ImagifyAI**

ImagifyAI is an advanced image editing application built with Next.js 14, Cloudinary AI, Clerk, MongoDB, Shadcn, and TypeScript, and is deployed on Vercel.

[Check it out here ImagifyAI](https://imagify-ai-ten.vercel.app/)

## Features

- Image Restoration, Image Recoloring, Image Generative Fill, Object Removal, Background Removal.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rameshchandra8520/ImagifyAI.git
   cd ImagifyAI
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   - Create a `.env.local` file in the root directory and add the following environment variables:
     ```env
      #MONGODB
      MONGODB_URL=
      
      #CLERK
      NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
      CLERK_SECRET_KEY=
      WEBHOOK_SECRET=
      
      NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
      NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
      NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
      NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
      
      #CLOUDINARY
      NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
      CLOUDINARY_API_KEY=
      CLOUDINARY_API_SECRET=
     ```

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
