Core Roles and Activities (Flip Cards)

An interactive, responsive web application designed for dental clinical training and education. This tool presents key professional responsibilities through a series of "flip cards" that reveal detailed descriptions when clicked.

🚀 Features

Interactive UI: Smooth 3D flip animations using CSS perspectives.

Responsive Design: Fully responsive grid layout that adapts from mobile (1 column) to desktop (3 columns) using Tailwind CSS.

Dynamic Content: Cards are generated dynamically via JavaScript from a data object, making it easy to update or expand content.

Modern Aesthetics: Uses the 'Inter' font family and a professional purple/green color palette suitable for clinical or educational environments.

🛠️ Technology Stack

HTML5: Semantic structure.

Tailwind CSS: Utility-first framework for layout, spacing, and typography.

Vanilla JavaScript: Logic for dynamic rendering and interaction handling.

CSS3 Transitions: For the 3D "flip" effect.

📂 File Structure

The project is contained within a single index.html file for maximum portability and ease of deployment:

Styles: Custom CSS variables for brand colors and specific flip-card animations.

Layout: A container-based grid that houses the interactive elements.

Scripts:

coreActivities: The data array containing titles and descriptions.

createCardHtml(): Template function for card generation.

renderCards(): Initialization function to inject content into the DOM.

📖 Content Included

The application currently highlights seven core dental clinical activities:

Chairside Assistance

Clinical Preparation

Infection Control (IPC)

Workflow Management

Patient Support

Radiography (X-rays)

Inventory Control

🔧 Customization

To add or modify roles, update the coreActivities array in the <script> section:

{
    title: "Your New Role",
    description: "Detailed description of responsibilities goes here."
}


🌐 Deployment

Since this is a static single-file application, you can deploy it by:

Opening the index.html file in any modern web browser.

Hosting it via GitHub Pages, Netlify, or Vercel.

Embedding it into an LMS (Learning Management System) as an HTML asset.
