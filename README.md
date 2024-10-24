# LiveMTA
# MTA Live Status Web App

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Project Description

The MTA Live Status Web App provides users with real-time updates on MTA subway services. By entering their current station or train, users can find the best possible route to their destination while avoiding slowdowns and service disruptions. The app leverages real-time data from MTA's APIs to ensure accuracy and reliability.

## Features

- Real-time MTA service updates.
- Intelligent route planning to avoid delays.
- User-friendly interface with interactive maps.
- Autocomplete functionality for station inputs.
- Responsive design for desktop and mobile devices.

## Technology Stack

### Backend

- Node.js
- Express.js
- Axios
- Redis (for caching)
- GTFS-Realtime-bindings (for parsing MTA data)

### Frontend

- React.js
- Axios
- Mapbox GL JS
- React Autocomplete

## Installation

### Prerequisites

- **Node.js and npm** installed. Download from [Node.js official website](https://nodejs.org/).
- **Redis** installed and running locally or accessible remotely.
- **MTA API Key**: Register at [MTA Developer Resources](https://api.mta.info/#/AccessKey).
- **Mapbox Access Token**: Sign up at [Mapbox](https://www.mapbox.com/) to obtain a token.

### Backend Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/mta-live-status-app.git
   cd mta-live-status-app/backend
