# DevBook Store - Optional Frontend Assignment by Inchoo

This is a simple frontend bookstore application built as an optional assignment for Inchoo. It demonstrates the use of modern web technologies to create an interactive, responsive e-commerce-like interface.

## Technologies Used

- **Alpine.js**: 3.x.x - For reactive JavaScript and component state management
- **Tailwind CSS**: 4.2.1 - For utility-first CSS styling and responsive design
- **HTML5**: For semantic markup and structure

## Prerequisites

- Node.js (version 14 or higher recommended)
- npm (comes with Node.js)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/josip-paulik/devbook-store.git
   cd devbook-store
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Building the Project

To build the Tailwind CSS styles:

```bash
npm run build
```

For development with watch mode:

```bash
npm run buildWatch
```

## Running the Application

Since this is a static HTML application, simply open `index.html` in your web browser after building the styles.

The application includes:
- Responsive header with navigation and mobile drawer
- Interactive cart sidebar with quantity controls
- Book display with image gallery
- Star rating display
- Add to cart functionality for a single product

## Features

- **Responsive Design**: Works on desktop and mobile devices
- **Cart Management**: Add items, adjust quantities, remove items, view subtotal
- **Book Gallery**: Navigate through book images
- **Rating Display**: Visual star ratings using clip-path for precise control
- **Mobile Navigation**: Drawer-style menu for smaller screens

## Project Structure

- `index.html` - Main HTML file with Alpine.js data and markup
- `styles.css` - Custom styles including Inter font import
- `dist/output.css` - Compiled Tailwind CSS (generated)
- `package.json` - Project dependencies and scripts