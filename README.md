# Online Thrift Store

Welcome to the **Online Thrift Store** project! This application is a simple e-commerce platform focused on buying and selling second-hand sneakers. The project uses [JSON Server](https://github.com/typicode/json-server) for a mock backend and simple HTML/CSS/JS for the frontend.

---

## 🚀 Features

- Browse a collection of sneakers from different brands (Converse, Nike, Vans, etc.)
- View product details: price, size, condition, and status
- Easily add, edit, or remove products in the database (`db.json`)
- Responsive and easy-to-customize user interface
- Ready for deployment on platforms like [Render](https://render.com/)

---

## 🗂️ Project Structure

```
.
├── db.json         # Mock database for products (JSON Server)
├── index.html      # Main frontend file
├── styles.css      # CSS styles (if present)
├── script.js       # JS logic (if present)
├── README.md       # Project documentation
└── ...             # Other assets or files
```

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/allan6757/OnlineThriftStore.git
cd OnlineThriftStore
```

### 2. Install Dependencies

If using JSON Server, install it globally or locally:

```bash
npm install -g json-server
```
or
```bash
npm install json-server --save-dev
```

### 3. Start the Mock API

```bash
json-server --watch db.json --port 3000
```
This will run your fake API at [http://localhost:3000/products](http://localhost:3000/products).

### 4. Open the Frontend

Open `index.html` in your browser.  
If your app fetches data from the API, make sure URLs match your `json-server` port.

---

## 🛍️ Data Model

The `db.json` file contains a list of sneaker products with the following fields:
- `id` (string): Unique identifier
- `name` (string): Product name
- `price` (number): Price in your currency
- `size` (string): Size information
- `condition` (string): Product condition (new, used, mint)
- `image` (string): Image URL or base64
- `status` (string): Availability (e.g., available)

---

## 🌱 Extending the Project

- Add new product categories (e.g., clothing, accessories) by updating `db.json`
- Improve the UI with more HTML/CSS or frameworks like React
- Enhance functionality: cart, user login, payment integration, etc.

---

## 📦 Deployment

You can deploy the project for free using [Render](https://render.com/) or similar static hosting services.  
For the backend, Render can serve your `json-server` as a REST API.

---

## 📚 Topics Covered

- HTML, CSS, JavaScript (frontend basics)
- JSON Server (mock REST API)
- RESTful endpoints for CRUD operations
- Data modeling with JSON
- Basic e-commerce concepts

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repo, open issues, or submit pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

- [allan6757](https://github.com/allan6757)
