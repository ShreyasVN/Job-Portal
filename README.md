<div align="center">
  <h1 align="center">Job Portal</h1>
  <h3>
    A free and open source job hunting and recruiting solution build with React, Node, Express, MongoDB and TailwindCSS
  </h3>
</div>

<div align="center">
  <a href="https://www.jobportal.io"></a>
</div>

<br/>

## Features

- People can register as job seekers, build their profiles, and look for jobs matching their skill sets.
- Users can upload their existing resumes. If they do not have one, they should be able to fill out a form and have a resume built for them.
- People can apply directly to posted jobs.
- Companies can register, post jobs, and search job seeker profiles.
- Multiple representatives from a company should be able to register and post jobs.
- Company representatives can view a list of job applicants and can contact them, initiative an interview, or perform some other action related to their post.
- Registered users should be able to search for jobs and filter the results based on location, required skills, salary, experience level, etc

## Demo

## Tech Stack

- [React](https://react.dev/) - Library UI
- [Vite](https://vitejs.dev/) - Frontend Tooling
- [Express](https://expressjs.com) - Framework
- [Typescript](https://www.typescriptlang.org/) – Language
- [Tailwind](https://tailwindcss.com/) – CSS
- [shadcn/ui](https://ui.shadcn.com) - UI Components
- [Prisma](https://prisma.io) - ORM
- [MongoDB](https://www.mongodb.com/) - Database

## Getting Started

### Prerequisites

Here's what you need to be able to run Job Portal:

- Node.js (version>=18.18.0)
- Docker

### 1. Clone Repository

```shell
git clone git@github.com:drbarzaga/job-portal.git
cd job-portal
```

### 2. Running in docker

```shell
docker-compose up
```

### 3. Running locally

```bash
npm run install:all
npm run dev
```

> If you're going to run the application locally, make sure you have MongoDB installed on your computer and add the `MONGO_URI` environment variable to the server's `.env` file.

### 4. Open App in your browser

Visit [http://localhost:5137](http://localhost:5137) in your browser.

## Contributing

Job Portal is an open-source project and we welcome contributions from the community.

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

### Our Contributors ✨

<a href="https://github.com/drbarzaga/job-portal/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=drbarzaga/job-portal" />
</a>
