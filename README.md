# Razorpay Clone Website🚀

This project is a static website designed using HTML and Tailwind CSS. The website replicates the look and feel of the Razorpay landing page with a focus on modern UI and responsive design.

# Features

Responsive Design: Optimized for all devices using Tailwind CSS.

Navigation Bar: Includes smooth hover effects.

Dynamic Sections: Highlight features, services, and promotional content.

Footer: Contains links, social media icons, and company information.

# Tools and Technologies

HTML: Markup language for creating the structure.

Tailwind CSS: Utility-first CSS framework for styling.

# Tailwind CSS Installation and Setup

Follow these steps to install and run Tailwind CSS in your project.

## Prerequisites

Ensure you have:
- **Node.js** installed on your system.
- A code editor like **Visual Studio Code**.

---

## Steps to Install and Run Tailwind CSS

### 1. Initialize Your Project

1. Open your terminal and navigate to your project folder.
   ```bash
   mkdir my-project
   cd my-project
   ```

2. Initialize a `package.json` file:
   ```bash
   npm init -y
   ```

### 2. Install Tailwind CSS

1. Install Tailwind CSS via npm:
   ```bash
   npm install -D tailwindcss
   ```

2. Create the Tailwind configuration file:
   ```bash
   npx tailwindcss init
   ```

### 3. Configure Tailwind CSS

Update the `tailwind.config.js` file to include your HTML files:

```javascript
module.exports = {
  content: ['./*.html'],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### 4. Create Your Input CSS File

1. Create a new file named `input.css` in your project folder.

2. Add the following Tailwind directives to the file:
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```


### 5. Link the Output CSS File

1. In your `index.html` file, link the generated `output.css` file:

   ```html
   <link rel="stylesheet" href="output.css">
   ```

### 6. Start Building

Write your HTML and use Tailwind classes to style your content. Save your files and refresh your browser to see the changes.

---









  


