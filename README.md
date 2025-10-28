# Workshop-3-Hands-on-Tasks-JSON-HTTP-Axios

A simple Node.js + Express app that searches the **OMDb API** for movies (in this example, “Star Wars”) and displays results in an HTML table.

---

## 🔧 Prerequisites

- **Node.js** (v14 or newer recommended)
- **npm** (or **yarn**)
- An **OMDb API key** — get your own free key at  
  👉 [https://www.omdbapi.com/apikey.aspx](https://www.omdbapi.com/apikey.aspx)

---
1. **Clone this repository**
   ```bash
   git clone https://github.com/InkMakhova/ws3.git
   cd ws3
    ```
   
2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Add your OMDb API key**
   * Open the file movies.js

   * Replace the placeholder with your personal API key: 
    ```bash 
    const API_KEY = "YOUR_OMDB_API_KEY";
    ```

4. **Run Locally**
   ```bash
   npm start
   ```
5. **Open your browser and go to:**
   ```
   http://localhost:3000
   ```
