## 1. Bootstrap MovieApp

Objectives: To kickstart the development of your movie application using Next.js, you will set up a new project with TypeScript, ESLint, and Tailwind CSS. This foundational setup will help ensure your code is well-structured, maintainable, and styled efficiently from the beginning.

Instructions:

Create a New Next.js Project:
Open your terminal and run the following command to create a new Next.js app named alx-movie-app:
npx create-next-app@latest alx-movie-app --typescript --eslint --tailwind

## 2. Set up Header, Footer, Layout and landing page

Objectives: To create a cohesive user interface for your movie application, you’ll set up a consistent layout by implementing a header and footer. This will enhance navigation and provide a professional look to your app. Additionally, you’ll create a landing page to greet users.

Instructions:

Create Layout Component:

In the components/layout directory, create a new file named Layout.tsx. This component will wrap around your page content.

## 3. Add the movies pages to you project

Objective: Create a dedicated movies section in your CineSeek application that allows users to view a list of movies and individual movie details.

Instructions:

Create the MovieCard Component:

Create a new file named MovieCard.tsx in your components/commons directory.

## 0. Install Necessary Dependencies

Objective: Set up the next-pwa package to enable PWA features in our cine seek movie app.

Instructions:

Clone the repository from GitHub:
git clone https://github.com/YOUR_USER_NAME/alx-project-0x14.git alx-pwa-0x01
cd alx-movie-app

Install the next-pwa package from here
npm i @ducanh2912/next-pwa
npm i -D webpack
Verify the installation by checking the package.json file for "webpack": "^5.94.0" and "@ducanh2912/next-pwa": "^10.2.9"

## 1. Configure PWA in Next.js

Objective: Update the next.config.mjs file to integrate the next-pwa package.

Instructions:

Open the next.config.mjs file in the root directory.