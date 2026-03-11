# Universal Search Hub 🔍

A simple, clean, and functional web interface built with pure HTML to streamline searching across multiple platforms.

## 🚀 Features
- **YouTube Search**: Directly queries video results.
- **E-commerce Integration**: Search Amazon, Flipkart, and Meesho instantly.
- **Lightweight**: Zero JavaScript, zero CSS frameworks—just standard HTML forms.
- **Targeted Results**: Opens searches in new tabs to keep your hub active.

🌐 Live Demo:
[Live Link](https://sajjadali-fullstack.github.io/universal-search-hub/)

## 🛠️ How it Works
This project utilizes HTML `<form>` elements with specific `action` attributes and `name` parameters that match the query strings of the target websites:

| Platform | Query Parameter |
| :--- | :--- |
| YouTube | `search_query` |
| Flipkart | `q` |
| Amazon | `k` |
| Meesho | `q` |



## 📂 Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/universal-search-hub.git](https://github.com/YOUR_USERNAME/universal-search-hub.git)
