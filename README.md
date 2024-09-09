# Pexels Image Gallery - Next.js Project

This is a hobby project built using Next.js that allows users to search and display images from the Pexels API. The app includes a simple search functionality, making it easy to find pictures by keyword.

## Features

- Fetches images using the Pexels API.
- Search functionality that allows users to search for images by keyword.
- Zod is used for schema validation of the API response.
- Responsive design for desktop and mobile devices.
- Displays images using the Next.js `Image` component with custom styling.

## Tech Stack

- **Frontend**: Next.js, React
- **API**: The Pexels API is used to fetch images. The request is made using the fetchImages function in fetchImages.ts.
- **Validation**: Zod for schema validation
- **Styling**: Tailwind CSS for styling, Next.js `Image` component for optimized image loading

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have `Node.js` and `npm` installed.
- You have a Pexels API key. You can sign up and get one from [Pexels API](https://www.pexels.com/api/).

## Installation

1. Clone the repository
2. Install dependencies:

```
npm install
```

3. Set up environment variables:

Create a .env.local file in the root directory and add your Pexels API key:

PEXELS_API_KEY=your_api_key

## Start application

Run the development server:

```
npm run dev
```

Open http://localhost:3000 in your browser to see the app.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
