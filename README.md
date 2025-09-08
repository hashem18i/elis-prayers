# Eli's Prayers by Roffelitm - Universal PDF Download

## Purpose

This project is a simple, single-page web application designed to provide accessible Sephardic (Edut HaMizrach) prayer texts. It allows users to easily view various prayers and download them as high-quality, universally compatible PDF files for printing or offline use.

The main goal is to assist individuals with their prayers by offering a clean, user-friendly interface that works on any device with a modern web browser.

## Features

*   **Prayer Selection**: A dropdown menu to select from a list of daily prayers, blessings, and other resources.
*   **Live Filtering**: A search box to quickly filter the prayer list.
*   **Universal PDF Download**: Generate a PDF for any selected prayer or resource using `html2canvas` and `jspdf`.
*   **Dark/Light Mode**: Toggle between a light (parchment) and dark theme for comfortable reading. The theme preference is saved in the browser.
*   **Font Size Control**: Increase, decrease, or reset the font size of the Hebrew text for better readability.
*   **Responsive Design**: The layout is designed to work well on both desktop and mobile devices.
*   **"About Us" Modal**: Provides information about the project and its creator.
*   **Return to Top Button**: Easily navigate back to the top of the page.

## Setup

This project is self-contained in a single `index.html` file and requires no complex setup or build process.

1.  **Clone or download the repository.**
2.  **Open `index.html` in a modern web browser** (such as Chrome, Firefox, Safari, or Edge).

That's it! The application will be fully functional. All external libraries (TailwindCSS, jsPDF, html2canvas) are loaded from a CDN, so an internet connection is required for them to load.

## Usage

1.  **Select a Prayer**: Use the dropdown menu labeled "-- Choose a Prayer or Resource --" to pick the prayer you wish to view.
2.  **Filter Prayers**: If you know the name of the prayer, you can type it into the "סנן תפילות..." (Filter prayers...) search box to narrow down the options in the dropdown.
3.  **Adjust Font Size**: Once a prayer is displayed, a font control bar will appear. Use the `A+` button to make the text larger, `-A` to make it smaller, and `A` to reset to the default size.
4.  **Toggle Theme**: Click the sun/moon icon in the header to switch between light and dark modes.
5.  **Download as PDF**: Click the "Download as PDF" button below the prayer text to generate and save a PDF version of the content.
6.  **View Information**: Click the "About Us" button in the header to learn more about the project.
