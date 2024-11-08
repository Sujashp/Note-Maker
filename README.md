# Easy Notes Maker

Easy Notes Maker is a simple, web-based note-taking application that enables users to create and customize notes with rich formatting options and export them to PDF. This application allows you to add images, customize font styles, background colors, and more, all within a single-page interface.

## Features

- **Customizable Fonts**: Change font color, size, style, and family for your notes.
- **Text Alignment**: Align text to the left, center, or right.
- **Bullet and Numbered Lists**: Organize your notes using bullet points or numbers.
- **Background Customization**: Apply background colors to notes.
- **Image Insertion**: Upload images directly into your notes.
- **Export to PDF**: Download notes as a PDF file for easy sharing and storage.

## Getting Started

### Prerequisites

To run Easy Notes Maker locally, you need:
- A modern web browser (e.g., Chrome, Firefox, Safari).
- Internet access (for loading external libraries).

### Installation

1. Clone or download this repository.
2. Open the `index.html` file in your browser to start using the application.

### Usage

1. **Open the Application**: Open the `index.html` file in a browser.
2. **Create a Note**: Click inside the title and content fields to start typing.
3. **Customize Your Note**:
   - Use the color picker and dropdown menus in the **Controls** section to customize font color, size, style, and family.
   - Use alignment buttons to adjust the text alignment.
   - Add bullet or numbered lists as needed.
4. **Add an Image**: Click **Add Photo** to insert images. Select the image file to upload.
5. **Export as PDF**: Click the **Export to PDF** button to save your note as a PDF file.

## Code Structure

- **HTML Structure**: Defines the main layout, including a header, controls, and editable areas for the note's title and content.
- **CSS Styling**: Styles the elements for an organized, visually pleasing interface.
- **JavaScript Functionality**:
  - Adds interactive functions like font color and background color customization.
  - Allows insertion of images and alignment of text.
  - Includes `html2pdf` library integration for exporting notes to PDF.

## Libraries Used

- **html2pdf.js**: A JavaScript library for converting HTML content into a downloadable PDF.

## Screenshots

| Main Interface | Exported PDF |
| -------------- | ------------ |
| Screenshot of note interface | Screenshot of exported PDF |

## License

This project is open-source and available for free use.
