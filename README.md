# The Movie Databasee (IMDb Clone)

Welcome to the IMDb Clone project! This project is built using Next.js 14 and Tailwind CSS, with data fetched from the TMDB API. The aim is to create a movie database website similar to IMDb, featuring functionalities such as movie listings, detailed movie pages, search, and dark mode.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Home Page:** Displays a list of popular movies.
- **Movie Details:** Each movie has its own detailed page with information such as synopsis, cast, and ratings.
- **Search:** Users can search for movies by title.
- **Dark Mode:** Toggle between light and dark modes.
- **Loading Effects:** Smooth loading animations.
- **Error Handling:** User-friendly error messages for failed data fetches.

## Demo

Check out the live demo of the project:

[IMDb Clone Demo](https://github.com/yusifhuseini/imdb_clone)

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yusifhuseini/imdb_clone.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd imdb_clone
    ```
3. **Install dependencies:**
    ```bash
    npm install
    ```
4. **Create a `.env.local` file in the root directory and add your TMDB API key:**
    ```env
    NEXT_PUBLIC_TMDB_API_KEY=your_tmdb_api_key_here
    ```

## Usage

To run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

To build the project for production:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

## Folder Structure

The project's folder structure is organized as follows:

```plaintext
imdb_clone/
├── public/
│   ├── favicon.ico
│   └── ...
├── src/
│   ├── components/
│   ├── pages/
│   │   ├── _app.js
│   │   ├── index.js
│   │   └── movie/
│   ├── styles/
│   ├── utils/
│   └── ...
├── .env.local
├── .gitignore
├── package.json
├── README.md
└── ...
```

## Technologies

- **Next.js 14:** Framework for server-side rendering and static site generation.
- **Tailwind CSS:** Utility-first CSS framework for rapid UI development.
- **TMDB API:** Source of movie data.
- **Vercel:** Hosting platform for deploying the application (optional).

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


## Created by Huseini Yusif

- **GitHub:** [yusifhuseini](https://github.com/yusifhuseini)
- **Facebook:** [huseiniyusif1](https://x.com/huseini_yusif)
- **Twitter(X):** [huseini_yusif](https://x.com/huseini_yusif)
- **LinkedIn:** [huseiniyusif](https://www.linkedin.com/in/huseiniyusif/)

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

---
