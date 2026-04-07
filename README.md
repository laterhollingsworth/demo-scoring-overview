# Lead Scoring Static Webpage

This project is a static webpage for a lead scoring application. It includes all necessary files and configurations to run the application in a web browser.

## Project Structure

```
lead-scoring-static
├── public
│   ├── index.html            # Main HTML file serving as the entry point
│   ├── app.repackages.js     # JavaScript code for the application
│   └── app.repackages.js.LICENSE.txt # License information for the JavaScript code
├── src
│   └── (original-source-files) # Original source files for the application
├── .gitignore                # Specifies files to be ignored by Git
├── package.json              # npm configuration file
└── README.md                 # Documentation for the project
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd lead-scoring-static
   ```

2. **Install dependencies**:
   If there are any dependencies listed in `package.json`, run:
   ```
   npm install
   ```

3. **Build the project**:
   If applicable, build the project using:
   ```
   npm run build
   ```

4. **Open the application**:
   Open `public/index.html` in your web browser to view the application.

## Publishing the Project

To publish this project as a static webpage, you can follow these steps:

1. Ensure that all your static files (HTML, CSS, JS) are in the `public` directory.
2. Use a static site hosting service like GitHub Pages, Netlify, or Vercel.
3. For **GitHub Pages**, push your code to a GitHub repository and enable GitHub Pages in the repository settings, selecting the `public` directory as the source.
4. For **Netlify** or **Vercel**, you can drag and drop the `public` folder into their web interface or connect your GitHub repository for automatic deployment.

## License

Refer to `app.repackages.js.LICENSE.txt` for license information regarding the JavaScript code used in this project.