# TikTok Clone

Welcome to TikTok Clone! This project is a replica of the popular social media platform TikTok, built with React.js, TypeScript, GraphQL, Nest.js, Prisma, PostgreSQL, Tailwind CSS, Apollo, and Codegen.

## Table of Contents

- [TikTok Clone](#tiktok-clone)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Technologies Used](#technologies-used)
  - [Contributing](#contributing)
  - [License](#license)

## Features

- User authentication and authorization
- Create, edit, and delete videos
- Like and comment on videos
- Follow and unfollow other users
- Explore trending and new videos
- Search for videos and users
- Responsive design for mobile and desktop

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/tiktok-clone.git
```

2. Navigate into the project directory:

```bash
cd tiktok-clone
```

3. Install dependencies:

```bash
npm install
```

4. Set up the environment variables:

Create a `.env` file in the root directory and add the following variables:

```dotenv
DATABASE_URL=your_postgres_database_url
```

5. Run database migrations:

```bash
npx prisma migrate dev --name init
```

6. Start the development server:

```bash
npm run dev
```

## Usage

Once the development server is running, you can access the TikTok Clone application at `http://localhost:3000` in your web browser.

## Technologies Used

- React.js
- TypeScript
- GraphQL
- Nest.js
- Prisma
- PostgreSQL
- Tailwind CSS
- Apollo
- Codegen

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

## License

This project is licensed under the [MIT License](LICENSE).
