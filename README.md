# Spot Picker

A React application for creating and managing your travel bucket list. Browse through carefully curated destinations worldwide and save places you'd like to visit, with automatic sorting based on your location.

## Features

- Browse a curated collection of worldwide travel destinations
- Location-based sorting of places using geolocation
- Save favorite destinations to a personal collection
- Persistent storage using localStorage
- Responsive image grid layout
- Modal confirmations with progress bars
- Smooth animations and transitions

## Technical Stack

- React 19 with Hooks (useState, useRef, useCallback, useEffect)
- Vite for build tooling and development
- CSS3 with modern features (Grid, Flexbox, Animations)
- HTML5 Geolocation API
- Local Storage for data persistence
- React Portals for modal dialogs

## Project Structure

```
src/
  ├── components/           # React components
  │   ├── DeleteConfirmation.jsx
  │   ├── Modal.jsx
  │   ├── Places.jsx
  │   └── ProgressBar.jsx
  ├── assets/              # Image assets
  ├── App.jsx             # Main application component
  ├── data.js            # Places data
  ├── loc.js             # Location utilities
  ├── index.css          # Global styles
  └── main.jsx           # Application entry point
```

## Core Functionality

- Geolocation sorting using Haversine formula
- Responsive image grid with hover effects
- Local storage synchronization
- Modal-based confirmations
- Progress tracking for actions
