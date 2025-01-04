# Portfolio Showcase

A personal portfolio website built with Next.js, showcasing projects, blog posts, and contact information.

## Features

- Project Showcase: A curated selection of projects, each with its own details page.
- Blog: A collection of articles and stories, with support for dynamic routing.
- Contact: A simple contact page with a form and social media links.
- Responsive Design: A mobile-friendly design that adapts to different screen sizes.

## Getting Started

- Clone the repository: git clone https://github.com/Hamid6426/portfolio-showcase.git
- Install dependencies: npm install
- Start the development server: npm run dev
- This will start the front-end as well as back-end concurrently
- Open http://localhost:3000/ in your browser to see the website in action
- Confirm if the back-end is running by checking the logs in the terminal

## Use for Yourself

- Follow the "Getting Started" steps to clone and run the project.
- Add a `.env` file in the root directory and include the necessary environment variables.
- Set up a MongoDB cluster and update the `.env` file with the database connection string.


## Project Structure

- The project is organized into the following folders:
- packages/backend: Backend code, including Prisma schema and API routes.
- packages/frontend: Frontend code, including Next.js pages, components, and utilities.
- public: Static assets, such as images and videos.

## Technologies Used

- Next.js: A popular React-based framework for building server-side rendered and statically generated websites.
- Tailwind CSS: A utility-first CSS framework for building custom user interfaces.
- Prisma: A modern ORM for Node.js and TypeScript, used for database modeling and querying.

## Contributing
Contributions are welcome! If you'd like to report a bug, suggest a feature, or submit a pull request, please feel free to do so.

## License
This project is licensed under the MIT License. See LICENSE for details.

## Acknowledgments

- Thanks to Vercel for providing the Next.js framework and hosting platform.
- Thanks to the Tailwind CSS team for creating a fantastic utility-first CSS framework.
- Thanks to the Prisma team for building a powerful and intuitive ORM.

---

```
root/
├── packages/
│   ├── backend/
│   │   ├── prisma/
│   │   ├── src/
│   │   │   ├── controllers/
│   │   │   ├── services/
│   │   │   ├── utils/
│   │   │   ├── routes/
│   │   │   ├── index.ts
│   │   ├── package.json
│   └── frontend/
│       ├── public/
│       │   ├── images/
│       │   ├── videos/
│       │   └── favicon.ico
│       ├── app/
│       │   ├── layout.tsx
│       │   ├── page.tsx
│       │   ├── projects/
│       │   │   ├── layout.tsx
│       │   │   ├── page.tsx
│       │   │   └── [slug]/
│       │   │         └── page.tsx
│       │   ├── blog/
│       │   │   ├── layout.tsx
│       │   │   ├── page.tsx
│       │   │   └── [slug]/
│       │   │         └── page.tsx
│       │   ├── about/
│       │   │   └── page.tsx
│       │   ├── contact/
│       │   │   └── page.tsx
│       │   ├── components/
│       │   │   ├── ProjectCard.tsx
│       │   │   ├── BlogPostCard.tsx
│       │   │   ├── SocialLinks.tsx
│       │   │   ├── Header.tsx
│       │   │   └── Footer.tsx
│       │   └── utils/
│       │       ├── api.ts (API Client)
│       │       └── constants.ts (Constants)
│       ├── next.config.js
│       ├── tailwind.config.js
│       ├── postcss.config.js
│       └── package.json
├── .eslintrc.json
├── tsconfig.json
└── package.json
```