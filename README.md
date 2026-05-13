# Plant Shop App
## Description

The Plant Shop App is a simple React application that allows users to browse, search, add, and manage plants. It fetches plant data from a local API and provides interactive features such as searching plants by name and adding new plants to the collection.

## Features
1. Display all plants from an API on page load
2. Search plants by name in real time
3. Add a new plant using a form
4. View plant details including name, image, and price
5. Automatically updates the plant list after adding a new plant
6. Uses controlled form inputs in React

## Technologies Used
React
JavaScript (ES6+)
Fetch API
JSON Server (for backend)
CSS

## Installation

*** Clone the repository: ***

git clone (https://github.com/wanja-juma/react-hooks-plantshop-cr-vite.git)

*** Navigate into the project folder: ***

cd plant-shop-app

*** Install dependencies: ***

npm install

*** Start the backend server (JSON Server): ***

npx json-server --watch db.json --port 6001

*** Start the React app: ***

npm run dev

### How It Works
1. Fetch Plants

On page load, the app fetches plants from:

http://localhost:5173/plants

and stores them in state.

Users can type into the search bar to filter plants by name:

* Case-insensitive search
* Updates results instantly

3. Add New Plant

Users can add a plant using a form:

* Name
* Image URL
* Price

After submission:

* Data is sent to the backend
* New plant is added to the UI immediately
4. Plant Display

Each plant card shows:

* Image
* Name
* Price
* Stock status toggle (In Stock / Out of Stock)

### Project Structure

src/
├── components/
│   ├── App.jsx
│   ├── Header.jsx
│   ├── PlantPage.jsx
│   ├── PlantList.jsx
│   ├── PlantCard.jsx
│   ├── NewPlantForm.jsx
│   └── Search.jsx
├── index.js
├── index.css

*** Display Image ***

src\assets\Screenshot 2026-05-13 143905.png

### Future Improvements
Edit plant details
Delete plants
Persist stock status to backend
Add categories or plant types
Improve UI styling

### Author
Ruth Wanja Juma

Developed as a React learning project.
