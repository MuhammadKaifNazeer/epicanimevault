# Epic AnimeVault - Open Source Anime Information Aggregator

![Epic AnimeVault](public/ScreenShots/EpicAnimeVault.png)

## Overview

Epic AnimeVault is an open-source project that leverages the Shikimori API to aggregate and display anime-related information. Built with Next.js, Framer Motion, and TypeScript, it offers a server-side rendering setup for optimal performance. Whether you're an anime enthusiast or a developer, Epic AnimeVault provides a platform to explore, discover, and contribute to the world of anime.

## Features

- **Shikimori Integration:** Utilizes the Shikimori API to fetch and display anime details, ratings, and more.
- **Explore:** Easily explore a vast collection of anime titles.
- **Contribution:** Contribute to the anime community by adding new entries or updating existing information.
- **User-Friendly Interface:** A clean and intuitive interface for a seamless user experience.
- **Infinite Scroll with Animation:** Enjoy a dynamic user experience with infinite scroll and smooth animations powered by Framer Motion.

## Tech Stack

- **Next.js:** A React framework for server-side rendering, providing a fast and efficient web development experience.
- **Framer Motion:** A React animation library for creating smooth, interactive animations.
- **TypeScript:** A typed superset of JavaScript that enhances code quality and developer productivity.

## Getting Started

### Prerequisites

- Node.js installed (https://nodejs.org/)
- Git installed (https://git-scm.com/)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/MuhammadKaifNazeer/epicanimevault.git

    ```git remote set-url origin https://github.com/MuhammadKaifNazeer/epicanimevault.git



2. Navigate to the project directory:

    ```bash
    cd epicanimevault
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Obtain your Shikimori API credentials. Visit [Shikimori API](https://shikimori.one/api) for more information.

    ```env
    SHIKIMORI_API_BASE_URL=https://api.shikimori.one
    SHIKIMORI_CLIENT_ID=your_client_id
    SHIKIMORI_CLIENT_SECRET=your_client_secret
    ```

### Usage

Run the following command to start the development server:

```bash
npm run dev

