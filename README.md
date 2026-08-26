# 🌍 Around the World

A responsive, interactive web application that integrates with the [REST Countries API](https://studies.cs.helsinki.fi/restcountries/api/all) to display detailed information about countries worldwide. 

**Live Demo:** (https://around-the-world-8ssg-oou69m2hu-hassan-ae68.vercel.app/)

## ✨ Features

- **See all countries** from the API on the homepage.
- **Search for a country** using an input field.
- **Filter countries** by region (Africa, America, Asia, Europe, Oceania).
- **Click on a country** to see more detailed information on a separate page.
- **Toggle the color scheme** between light and dark mode.
- **Performance Optimized:** Uses `localStorage` to cache API data, reducing network requests and improving load times.

## 🛠️ Tech Stack

- **Framework:** [React.js](https://react.dev/) (v19) with [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Routing:** [React Router v7](https://reactrouter.com/)
- **Components:** [React Select](https://react-select.com/) for custom dropdowns
- **Code Quality:** ESLint (Oxlint) & Prettier

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
Make sure you have Node.js installed on your machine.

### Installation

1. Clone the repo:
   ```sh
   git clone [https://github.com/your-username/around-the-world.git](https://github.com/your-username/around-the-world.git)
2. cd around-the-world
3. npm install
4. npm run dev
5. Open http://localhost:5173 in your browser.

## 📂 Folder Structure
/src/components: Contains reusable UI components (Header, CountryCard, SearchInput, etc.)

/src/pages: Contains the main page views (Home, Country details, Layout)

/src/useFetchData.js: Custom hook handling API requests, loading states, and localStorage caching.

## Designed & Developed by 
# Hassan Mahdi
