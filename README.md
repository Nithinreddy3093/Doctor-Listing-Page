# Doctor-Listing-Page

This project is a dynamic Doctor Listing Page developed as part of a campus assessment challenge. It provides users with an interactive interface to search, filter, and sort doctors based on various criteria — all handled entirely on the client side.

## Features

- 🔍 **Autocomplete Search Bar**: Search for doctors by name with instant suggestions.
- 🩺 **Filter Panel**:
  - Consultation Type: Video or In-Clinic (single select).
  - Specialties: Multi-select checkboxes.
- ↕️ **Sort Options**: Sort doctors by fees (ascending) or experience (descending).
- 🧠 **Fully Client-Side Logic**: All filtering, searching, and sorting is done in the browser.
- 🔗 **URL Syncing**: Filters and search states are reflected in the URL as query parameters and persist with browser navigation.

## Technologies Used

- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui

## Getting Started

Make sure you have **Node.js** and **npm** installed.

```bash
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate into the project directory
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm install

# Start the development server
npm run dev
API Used
Doctor data is fetched from the following URL: https://srijandubey.github.io/campus-api-mock/SRM-C1-25.json

Note
All features (search, filter, sort) are implemented on the client side after the initial API call. The page supports URL query params to retain filter/search state.

