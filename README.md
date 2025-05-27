# Simple Blog Application


This is a straightforward, client-side blog application built using **HTML**, **CSS**, and **vanilla JavaScript**. It fetches blog post data from a local JSON file, renders posts on a homepage, allows filtering by category or keyword, and provides a single-page view for individual blog posts.


---


## ✨ Features


- **Homepage Display**: All blog posts are rendered dynamically on the `index.html` page.

- **Data from JSON**: Blog content is stored in `data/posts.json`.

- **Filtering**:

  - **Search by Keyword**: Filter posts by keywords in titles and content.

  - **Filter by Category**: Narrow down posts via a dropdown selection.

- **Single Post View**: Clicking a post card opens `blog-post.html` with full post content.

- **Responsive Design**: Basic CSS ensures good display across screen sizes.


---


## 📁 Project Structure

blog-app/

├── index.html # Main blog homepage

├── blog-post.html # Single blog post template

├── style.css # CSS styles

├── script.js # JavaScript logic & rendering

├── data/

│ └── posts.json # Blog post data

└── images/

├── post-image-1.jpg

├── post-image-2.jpg


## 🚀 Getting Started


To run the app locally, use a simple web server. Opening the HTML file directly in a browser will result in CORS errors due to JSON fetching restrictions.


### ✅ Prerequisites


- A modern web browser (e.g. Chrome, Firefox, Edge)


---


## 🔧 Running the Application


VS Code Live Server (Recommended)


1. Install the **Live Server** extension by *Ritwick Dey*.

2. Open the `blog-app` folder in VS Code.

3. Right-click on `index.html` or `blog-post.html`.

4. Select **"Open with Live Server"**.


