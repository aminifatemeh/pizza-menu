# Fast React Pizza Co.

## 🍕 Overview
This is a simple **React-based pizza menu** for "Fast React Pizza Co." The app displays a list of available pizzas, their ingredients, and prices. If a pizza is sold out, it is visually marked as unavailable. The footer dynamically updates based on the current time to indicate whether the restaurant is open.

## 🚀 Features
- Displays a list of pizzas with images, ingredients, and prices.
- Marks sold-out pizzas with a special style.
- Shows a restaurant opening/closing message based on the current time.
- Includes an "Order" button when the restaurant is open.

## 🛠️ Technologies Used
- **React** (Functional Components, Props, JSX)
- **JavaScript (ES6+)**
- **CSS** (for styling)

## 📂 Project Structure
```
📦 fast-react-pizza
├── 📂 public
│   ├── 📂 pizzas  # Folder for pizza images
│   │   ├── focaccia.jpg
│   │   ├── margherita.jpg
│   │   ├── spinaci.jpg
│   │   ├── funghi.jpg
│   │   ├── salamino.jpg
│   │   ├── prosciutto.jpg
│   ├── index.html
├── 📂 src
│   ├── index.js  # Entry point of the app
│   ├── index.css # Styling for the app
│   ├── App.js    # Main component
│   ├── components
│   │   ├── Header.js  # Header component
│   │   ├── Menu.js    # Menu component (maps over pizza data)
│   │   ├── Pizza.js   # Individual pizza component
│   │   ├── Footer.js  # Footer component (handles opening hours)
│   │   ├── Order.js   # Order button and message
│   ├── data.js   # Pizza data (array of objects)
├── package.json  # Project dependencies and scripts
└── README.md
```

## 📜 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/fast-react-pizza.git
cd fast-react-pizza
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Start the Development Server
```bash
npm start
```
This will start the React development server, and the app will be available at `http://localhost:3000/`.


💡 **Made with ❤️ using React!**

