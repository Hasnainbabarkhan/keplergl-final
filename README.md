# Kepler Map App

This is a React application that integrates Kepler.gl for interactive geospatial visualization.

## Prerequisites
Ensure you have the following installed:
- Node.js (>= 14.x)
- npm or yarn

## Installation
Clone the repository and install dependencies:

```sh
# Install dependencies
npm install
```

## Usage
Run the development server:

```sh
npm start
```

The app will be available at `http://localhost:3000/`.

## Dependencies
- React
- Redux Toolkit
- Kepler.gl
- Mapbox GL JS

## Configuration
This app requires a Mapbox API key for full functionality. Update the `REACT_APP_MAPBOX_API` prop in `.env` with your token and integrate in `App.js`:

```js
<KeplerGl
      id="covid"
      mapboxApiAccessToken={process.env.REACT_APP_MAPBOX_API}
      width={window.innerWidth}
      height={window.innerHeight}
    />
```

