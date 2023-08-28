# GiveMeMovies2 - AI-Powered Movie Recommendation Web App

Welcome to GiveMeMovies2, a web application that leverages AI to recommend movies based on user prompts. The core feature allows users to type in a description or set of criteria, and the app suggests movies that match, allowing users to save these recommendations to a list.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Tech Stack](#tech-stack)
- [Contributors](#contributors)

## Introduction

GiveMeMovies2 is an interactive web application that uses Natural Language Processing (NLP) to recommend movies to users based on specific prompts. Users can type in criteria such as genre, actor, director, and maximum watch time. The app then fetches movie suggestions that align with the given criteria and allows users to save these to a list.

## Getting Started

### Prerequisites
- Node.js
- NPM

### Installation and Running

#### Client
1. Navigate to the client folder.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

#### Server
1. Navigate to the server folder.
2. Run `npm install` to install dependencies.
3. Run `nodemon index.js` to start the backend server.

> **Note:** Before running the server, make sure to set up a `.env` file in the server directory with the following environment variables:
> - `TBMD_PERSON_ID=...`
> - `OPENAI_API_KEY=...`
> - `TMDB_API_KEY=...`

## Tech Stack

- **Client**: React
- **Server**: Node.js, Koa
- **APIs**: OpenAI GPT-3.5, TMDB API
- **Testing**: Jest, React Testing Library, Supertest

## Contributors

- Carlos Bárcena Bescansa
  - [LinkedIn](www.linkedin.com/in/carlos-barcena-bescansa)
  - [GitHub](https://github.com/carlosbarbes)
- Atai Ismaiilov
  - [LinkedIn](https://www.linkedin.com/in/atai-ismailov)
  - [GitHub](https://github.com/Atai-Ismaii)

- Pablo Flores (Original Creator)
  - [LinkedIn](https://www.linkedin.com/in/pablo-flores)
  - [GitHub](https://github.com/pabloflores)
