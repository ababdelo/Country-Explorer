# Country Explorer: Discover Countries Around the World

## Overview

Curious about the countries around the world? Country Explorer makes it easier to discover them.

Country Explorer is a web application built with React that uses the REST Countries API to display information about countries around the world. Browse countries, explore their flags and basic information, and find the details you're looking for through a simple interface.

## Previews

*Screenshots will be added once the interface is ready.*

## Planned Features

- **Country Catalog**: Browse a collection of countries retrieved from the REST Countries API.
- **Country Information**: View country flags, names, capitals, and regions.
- **Search**: Find countries by their names.
- **Region Filters**: Filter the catalogue by geographical region.
- **Loading & Error States**: Clear feedback while retrieving country data or when a request fails.
- **Responsive Design**: An interface adapted to desktop, tablet, and mobile screens.

## Project Structure

```text
Country-Explorer/
├── .github/
│   ├── CODEOWNERS
│   └── workflows/
│       ├── ci.yml
│       └── deploy.yml
├── public/
├── src/
│   ├── assets/
│   │   ├── fonts/
│   │   └── images/
│   ├── components/
│   │   └── App.jsx
│   ├── services/
│   ├── styles/
│   │   └── index.css
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── LICENSE
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Branching Strategy

The project follows a simple Git workflow:

- `dev`: Integration and testing of new features.
- `main`: Stable and reviewed changes.
- `prod`: Production-ready releases.

New features are developed in dedicated branches created from `dev`.
Once completed, they are submitted through Pull Requests for review
before being merged.

## How to Run

### Prerequisites

- [Node.js](https://nodejs.org/)
- Any modern web browser

### Steps

1. **Clone the repository:**

```bash
git clone https://github.com/ababdelo/Country-Explorer.git
cd Country-Explorer
```

2. **Install dependencies:**

```bash
npm install
```

3. **Start the development server:**

```bash
npm run dev
```

4. **Open in Browser:**

Vite will display the local development URL in your terminal. Open it in your preferred browser.

## API Reference

Country Explorer uses the [REST Countries API](https://restcountries.com/) to retrieve country information.

## Contributing

To contribute to Country Explorer:

1. Create a feature branch from `dev`.
2. Implement your changes.
3. Commit and push your branch.
4. Open a Pull Request targeting `dev`.
5. Request a review from a teammate.
6. Merge after the required approval and successful CI checks.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [REST Countries](https://restcountries.com/) for providing country data.
- [React](https://react.dev/) for the user interface library.
- [Font Awesome](https://fontawesome.com/) for the icons components.
- [icons8](https://icons8.com/) for providing the free aesthetic icons and logos.
- [StorySet](https://storyset.com/) for providing the free beautifull customized illustrations.

## Team
- **Abderrahmane Abdelouafi (ababdelo)** - [GitHub URL](https://github.com/ababdelo)
- **FullName (username)** - [GitHub URL](https://github.com/username)
- **FullName (username)** - [GitHub URL](https://github.com/username)

<p align="center">Thanks for stopping by and taking a look!</p>