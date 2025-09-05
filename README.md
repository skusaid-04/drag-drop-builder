# Drag & Drop Website Builder

## Overview
This is a prototype drag-and-drop website builder built with React.Users can drag elements onto a canvas,customize their properties via a form, and export the final design as clean HTML.

## Features
- Drag & drop elements from sidebar
- Edit properties (color, text, alignment, font size, select options etc.)
- Export HTML of final design
- Responsive layout for desktop & mobile
- Easy to extend with new elements

## Architecture
- **React** for state management
- **Sidebar** -> draggable elements
- **Canvas** -> drop area to arrange elements
- **Properties Panel** -> form to edit selected element
- **exportHTML()** -> converts canvas state into final HTML code

## How to Run
1. unzip project
2. Install dependencies
- **npm install**
3. Start development server
- **npm start**
4. Open [http://localhost:3000](http://localhost:3000)
