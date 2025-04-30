# 🔎 Project: Dynamic Search App

## 📌 Description
This is a web application that allows users to perform **dynamic searches** by sending HTTP requests to an external API. In this example, the app uses the **Rest Countries API**, but the search logic is generic and can be adapted to any data source. As users type their query, the app filters and displays results in a user-friendly format.

## 🧰 Tech Stack
- **JavaScript (ES6+)**
- **HTML5 / CSS3**
- **Axios** — for HTTP requests
- **Lodash.debounce** — to optimize input event handling
- **Notiflix** — for user notifications
- **Parcel** — for project bundling

## 🔍 Key Features
- ✨ **Live Search**: API calls are debounced to reduce unnecessary requests
- 🧾 **Smart Result Display**:
  - If **1 match** is found — detailed info is shown (flag, capital, languages, population)
  - If **2–10 matches** — a list of country names is shown
  - If **more than 10** — a notification suggests refining the query
- ⚠️ **Error Notifications**: integrated with Notiflix to alert users of incorrect input or API issues
- 🌍 **Flexible Logic**: easy to adapt for other types of data (e.g., cities, products, movies)

## 🚀 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/RuslanZotsenko22/goit-js-hw-12.git
```

2. Navigate to the project directory:
```bash
cd goit-js-hw-12
```

3. Install dependencies:
```bash
npm install
```

4. Run the project:
```bash
npm start
```

5. Open your browser at:
```
http://localhost:1234
```

## 🌐 Live Demo
[Click to view live →](https://ruslanzotsenko22.github.io/goit-js-hw-12/)

---

Author: [Ruslan Zotsenko](https://github.com/RuslanZotsenko22) 🚀
