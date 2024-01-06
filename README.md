# Astro-Tina-Web

## Author
Kian Karbasy

## About This Project
This project is built using Astro with Tailwind CSS and Tina CMS for an enhanced blogging experience. It's designed to provide an intuitive way to manage and create blog content.

## How I Built This App

### Getting Started
1. **Astro Setup**
   - Executed `npm create astro@latest`.
   - Options selected:
     - Chose 'no git repo' as the project was already initialized in a git repository.
     - Selected 'Blog Template'.
     - Declined TypeScript integration.

2. **Adding Tailwind CSS**
   - Ran `npx astro add tailwind`.
   - Options selected:
     - Chose 'yes' for all options to fully integrate Tailwind CSS.

3. **Integrating Tina CMS**
   - Executed `npx @tinacms/cli@latest init`.
   - Options selected:
     - Chose 'yes' for all options to set up Tina CMS.

### Development Environment
- Node Version: v18.19.0
- Tested on Chrome browser.

## Running the Project Locally

To run the project on your local machine, follow these steps:

1. Navigate to the project directory:

`cd astro-tina`

2. Install dependencies:

`npm i`

3. Start development server:

`npm run dev`

## Making Edits Through Tina CMS

To edit content using Tina CMS:

1. **Accessing the Admin Panel**
- After running the project, open your browser (preferably Chrome) and go to `http://localhost:4321/admin/index.html`.

2. **Editing Blog Posts**
- Navigate to the 'blog' collection.
- Here, you can create, delete, and edit blog posts.

3. **Editing the Homepage**
- Go to the 'Homepage' collection.
- This section allows you to directly edit the homepage content and title.

---

Thank you for reviewing this technical assessment and my candidacy. I thoroughly enjoyed learning about Tina CMS and Astro.

