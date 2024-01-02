# Vue Basics Readme

This repository contains a simple web application built using Vue.js, showcasing the basics of Vue.js components and data binding. The application consists of a navigation bar and a page viewer component, allowing users to navigate between different pages and view their content dynamically.

## Project Structure

The project structure is as follows:

- **index.html**: The main HTML file that includes the Vue.js script and defines the structure of the application.

- **styles.css**: This file is not included in the provided code but can be added to customize the styling of the application.

## Dependencies

The project relies on the following external dependencies:

- **Bootstrap (v5.3.2)**: A popular CSS framework, hosted on [cdn.jsdelivr.net](https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css).

- **Vue.js (v3)**: The JavaScript framework for building user interfaces, loaded from [unpkg.com](https://unpkg.com/vue@3).

## Components

### 1. Navbar Component

The Navbar component is responsible for rendering the navigation bar. It includes a list of pages and a dynamic class binding to highlight the active page. Additionally, it provides a button to toggle the theme between light and dark.

#### Props

- **pages**: An array of page objects, each containing link information, page title, and content.

- **activePage**: The index of the currently active page.

- **navLinkClick**: A function to handle the navigation link clicks.

#### Methods

- **changeTheme()**: Toggles the theme between light and dark.

### 2. Page Viewer Component

The Page Viewer component displays the content of the currently active page. It takes a page object as a prop and dynamically renders the page title and content.

#### Props

- **page**: The page object containing link information, title, and content.

## Vue App Instance

The Vue app is created using `Vue.createApp` and mounted on the `<body>` element. It includes the data for managing the active page and theming, as well as two custom components: Navbar and Page Viewer.

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository.
2. Open the `index.html` file in a web browser.

## Usage

- Click on the navigation links to switch between pages.
- The content of the selected page will be displayed in the Page Viewer.
- Use the "Toggle Navbar" button to switch between light and dark themes.

Feel free to explore and modify the code to enhance your understanding of Vue.js and web development.
