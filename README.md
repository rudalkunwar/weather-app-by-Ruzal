# Weather App

Search any city and get current conditions plus a five-day forecast. Built with Create React App and deployed to GitHub Pages.

**Live:** https://weather-app-by-ruzal.vercel.app

## Features

- Search by city name, with geocoding suggestions
- Current temperature, conditions, feels-like and humidity
- Five-day forecast
- Responsive layout that works on mobile
- Recent searches kept in local storage

## Stack

| | |
|---|---|
| Framework | Create React App |
| Language | JavaScript |
| Styling | CSS |
| Icons | `react-icons` |
| Hosting | GitHub Pages via `gh-pages` |

## Running locally

```bash
git clone https://github.com/rudalkunwar/weather-app-by-Ruzal.git
cd weather-app-by-Ruzal
npm install
```

Create `.env.local` in the project root:

```bash
REACT_APP_WEATHER_API_KEY=your_key_here
```

Then:

```bash
npm start
```

## Deploying

```bash
npm run build
npm run deploy
```

`homepage` in `package.json` must point at the GitHub Pages URL, otherwise assets resolve to the wrong path after deploy.

## License

MIT
