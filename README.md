# JSON Tree Viewer

A React/Next.js and TypeScript-based application that renders any valid JSON structure as a collapsible tree. The application supports expanding and collapsing JSON objects and arrays, and allows users to copy the JSON path of any property to the clipboard.

## Features

- **Collapsible Tree Structure**: Any object or array can be expanded or collapsed. The root object is expanded by default, while child properties are collapsed.
- **Copy JSON Path**: Easily copy the "json path" of any property with a single click on the "create column" button.
- **State Persistence**: Nested properties retain their expanded/collapsed state even when their parent properties are toggled.
- **Responsive Design**: A clean and responsive UI following provided designs.
- **Bonus Animations**: Smooth transitions for expanding and collapsing tree nodes.

## Technical Stack

- **Frontend**: React/Next.js, TypeScript
- **State Management**: Zustand
- **Icons**: [Tabler Icons](https://tabler.io/icons)
- **UI Framework**: [Mantine](https://mantine.dev)

## How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/bitcooker/json-viewer.git
   cd json-viewer
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```
   The application should now be running on `http://localhost:3000`.

4. **Run the app in production mode**:
   ```bash
   npm run build
   npm start
   ```

## How to Use

- **Input JSON**: Paste your JSON in the textbox on the left side.
- **View JSON**: The structured JSON will be displayed in a tree format on the right.
- **Expand/Collapse**: Click on any object or array to expand or collapse its children.
- **Copy Path**: Click the "create column" button next to any property to copy its JSON path.

## Demo

You can check out the live version of this project [here](https://json-viewer-technical-test.vercel.app/).

## Design & Prototype

- **Design**: [Figma Design](https://www.figma.com/design/1wBUumrJAslNcgpPCY4ZvD/FE-Challenge-%5BDesigns%5D?node-id=0-1&t=6CAVxiIVGN8tRyem-1)
- **Prototype**: [Figma Prototype](https://www.figma.com/proto/1wBUumrJAslNcgpPCY4ZvD/FE-Challenge-%5BDesigns%5D?page-id=0%3A1&node-id=1-2&node-type=frame&viewport=-3797%2C-191%2C1.88&t=QDudUfymdbKWqhWj-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=1%3A2&show-proto-sidebar=1)

## Deployment

This project can be easily deployed on Vercel, Netlify, or Render. Follow their respective documentation for details on deploying React projects.