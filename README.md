Marketing Channel Expense Dashboard
This project is a simple, single-page web dashboard for visualizing marketing channel expenses. It allows users to upload a CSV file containing marketing spend data and view the information in interactive charts and a raw data table.

Features:
📊 Interactive Charts: Visualize monthly spend and total investment by channel using customizable bar, line, and pie charts.
📥 CSV Upload: Easily upload your own marketing expense data in a standard CSV format.
📝 Dynamic Data Table: View the raw data from your uploaded CSV file in a clean, scrollable table.

Project Setup:
Since this is a single HTML file that relies on client-side JavaScript, there's no complex setup required. You can run it directly in any modern web browser.

Requirements:
A modern web browser (e.g., Chrome, Firefox, Safari, Edge).
A CSV file with your marketing expense data. The CSV file must contain the following columns:
channel (e.g., "Social Media Ads")
month (e.g., "Jan", "Feb")
spend (e.g., "1500", "2000")

How to Run:
Save the Code: Save the provided HTML code into a file named index.html.
Open the File: Simply double-click the index.html file. It will automatically open in your default web browser.
Upload Data: On the dashboard, click the "Upload CSV" button and select your marketing expense CSV file. The charts and data table will automatically update with your information.

Technical Details:
This dashboard is built using the following libraries and technologies, all loaded via CDNs (Content Delivery Networks) directly within the HTML file:
HTML5 & CSS: The core structure and styling.
Tailwind CSS: A utility-first CSS framework for rapid UI development.
Chart.js: A powerful JavaScript library for creating interactive data visualizations.
PapaParse: A robust CSV parser for JavaScript, used to process uploaded CSV files.
