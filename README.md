# Blog Application 📝

This is a blog application built using **React.js**. It allows users to view a list of blog posts, read detailed blog content, and view author information. The application utilizes **React Router** for navigation and **CSS** for styling. Blog data is fetched from an external API.

## Features 🚀
- **Blog List View**: Displays a list of blog items, including topics, titles, and author details. 📋
- **Blog Details View**: Clicking on a blog item takes you to a detailed view of the blog, including the full content and author information. 📖
- **Responsive Design**: The layout is responsive, adapting to different screen sizes (mobile, tablet, desktop). 📱💻
- **Loading Spinner**: A loading spinner is shown while blog data is being fetched. ⏳

## Technologies Used ⚙️
- **React.js**: For building the user interface and managing state. ⚛️
- **React Router**: For routing between different views (Blog List and Blog Details). 🔄
- **Fetch API**: For fetching blog data from the API (`https://apis.ccbp.in`). 🌐
- **CSS**: For styling the application, including responsive design through media queries. 🎨

## File Structure 📂
```
src/
│
├── components/
│   ├── BlogItem.js          # Displays individual blog item in list view
│   ├── BlogItemDetails.js   # Displays detailed blog view
│   ├── BlogsList.js         # Displays the list of blogs
│   ├── Header.js            # Navbar component
│   ├── NotFound.js          # Displays a 404 error page
│   ├── About.js             # About page component
│   ├── Contact.js           # Contact page component
│   └── Loader.js            # Spinner component
│
├── App.js                   # Main application file with routing
├── index.css                # Global styles and media queries
└── App.css                  # App-specific styles

```


## Application Functionality 🛠️
- **Routing**: The application uses **React Router** for navigation between different routes:
  - `/` (Home): Displays a list of blog posts. 🏠
  - `/blogs/:id`: Displays detailed information of a selected blog post. 📑
  - `/about`: A static About page. 👤
  - `/contact`: A static Contact page. 📞
  - **404 Page**: Displays a Not Found page for any undefined routes. ❌

- **API Fetching**: 
  - **Blog List**: Fetches a list of blog items when the home page loads. 🔄
  - **Blog Details**: Fetches the detailed information of a specific blog post when clicked. 📡

## Live Demo 🌐

Check out the live version of the project here: [Live Demo](https://manojblogsreact.ccbp.tech)


<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/fetch-and-routing-practice-output.gif" alt="fetch and routing practice desktop output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

## Thank You! 💖
