# Spreadsheet Application

This is a Next.js-based spreadsheet application that mimics the functionality of a traditional spreadsheet with advanced features such as cell formatting, data validation, search and filter, pagination, and undo/redo functionality. The project is styled using Tailwind CSS and manages state with Zustand.

## Features

### Grid Rendering
- **Grid of 1000 Cells:** The application displays a grid with 1000 editable cells, efficiently rendered for performance.

### Cell Editing
- **Editable Cells:** Each cell in the grid can be edited by clicking on it.

### Data Storage
- **State Management:** Data entered in each cell is stored in memory using Zustand, ensuring persistence during interactions.

### Formatting Controls
- **Text Alignment:** Change text alignment (left, center, right) using the formatting controls.
- **Font Size:** Adjust font size using small, medium, and large options.

### Pagination
- **Pagination Controls:** Navigate through the grid using "Previous" and "Next" buttons, with 100 cells displayed per page.

### Search and Filter
- **Search:** Enter text in the search bar to filter cells that contain the search query.
- **Filter:** Apply filter criteria to further refine the displayed cells.

### Undo/Redo
- **Undo/Redo Functionality:** Use the "Undo" and "Redo" buttons to revert or reapply changes made to the cells.

## Repository

GitHub Repository: [Spreadsheet Application](https://github.com/Shuboy742/Spreadsheet_App)

## Setup

### Clone the Repository
To set up the project locally, clone the repository using the following command:

```bash
git clone https://github.com/Shuboy742/Spreadsheet_App.git
cd Spreadsheet_App

Install Dependencies

Install the required dependencies by running:
npm install

Run the Development Server:
npm run dev
