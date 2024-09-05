# Currency Converter

This is a responsive currency converter web application built with **React**, bundled using **Vite**, and styled with **Tailwind CSS**. The application fetches real-time currency exchange rates and provides easy conversion between different currencies, including NPR (Nepalese Rupee).

## Features

- Real-time currency conversion using [@fawazahmed0/currency-api](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@2024-03-06/v1/currencies/npr.json)
- Responsive design for desktop and mobile devices.
- Fast bundling and development with **Vite**.
- Clean, modern UI with **Tailwind CSS** for styling.
- Minimalistic and easy-to-use interface.

## Tech Stack

- **React**: JavaScript library for building user interfaces.
- **Vite**: Next-generation frontend tooling for fast build times.
- **Tailwind CSS**: Utility-first CSS framework for styling.

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Bipan101/currencyConverter.git

2. Navigate to the project directory:
    ```bash
    cd (your directory)

3. Install the dependencies:
    ```bash
    npm -i or npm install

4. Install Tailwind CSS:
   To include Tailwind CSS in the project, follow these steps:
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init

5. Configure Tailwind by adding the following to tailwind.config.js:
   ```
   /** @type {import('tailwindcss').Config} */
   module.exports = {
     content: [
       "./index.html",
       "./src/**/*.{js,ts,jsx,tsx}",
     ],
     theme: {
    extend: {},
     },
     plugins: [],
   }



6. Include Tailwind in your CSS by adding this to index.css or global.css:
   ```
      @tailwind base;
      @tailwind components;
      @tailwind utilities;
 if step 6) didn't work then try replacing by this :
    
      @import 'tailwindcss/base';
      @import 'tailwindcss/components';
      @import 'tailwindcss/utilities';


7. Start the development server:
    ```bash
       npm run dev


# API Information:

The project uses @fawazahmed0/currency-api to fetch the latest currency exchange rates.
Endpoint: https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@2024-03-06/v1/currencies/npr.json
The data is used to convert NPR/ to multiple currencies in real-time.

