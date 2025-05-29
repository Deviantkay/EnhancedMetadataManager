# Enhanced Metadata Manager

The Enhanced Metadata Manager is a versatile, user-friendly web application that allows you to manage, modify, and optimize image metadata. Whether you are a professional photographer, a content creator, or just someone who wants better organization of images, this tool is built for you.

You Can Access it Via [Netlify](https://exifly.netlify.app) or [Vercel](exifly.vercel.app)

## Features

### 1. Metadata Generation
- **AI-Powered Metadata**: Generate titles, subjects, and keywords for images automatically using the Gemini API.
- **File Renaming**: Optionally rename files based on generated titles.
- **Categorization**: Manually select or auto-detect categories for images.

### 2. Metadata Reading
- **Detailed Metadata Viewer**: Read and display both custom and technical EXIF metadata.
- **Comprehensive Data**: Includes titles, subjects, keywords, GPS data, camera settings, and timestamps.

### 3. Metadata Deletion
- **Privacy First**: Easily remove all metadata from images to protect sensitive information or minimize file size.

### 4. Image Conversion
- **Universal Format**: Convert images to JPEG format without quality loss.
- **Batch Conversion**: Process multiple files at once for efficiency.

## Installation and Setup

This tool is fully web-based and does not require installation. Simply open the `metadata_filler.html` file in any modern web browser to get started.

### Requirements
- A modern web browser (e.g., Chrome, Firefox, Edge).
- Active internet connection for Gemini API functionality.
- Gemini API keys for metadata generation.

## Usage Instructions

### 1. Launch the Application
Open the `index.html` file in your preferred browser.

### 2. Navigate Through Tabs
The application consists of four main tabs:
- **Generate Metadata**: Upload images and generate AI-powered metadata.
- **Read Metadata**: Upload an image to view detailed EXIF metadata.
- **Delete Metadata**: Remove metadata from selected images.
- **Images to JPEG**: Convert images of any format to high-quality JPEGs.

### 3. Generate Metadata
1. Upload images by clicking on the **Select Images** button.
2. Enter your Gemini API key(s) in the provided field.
3. Choose categories manually or enable auto-detection.
4. Optionally, enable the **Rename files based on generated titles** checkbox.
5. Click on the **Generate Metadata** button to process the files.
6. Download individual files or all files as a ZIP archive.

### 4. Read Metadata
1. Switch to the **Read Metadata** tab.
2. Upload an image to view its metadata.
3. All metadata fields, including technical and custom ones, will be displayed.

### 5. Delete Metadata
1. Switch to the **Delete Metadata** tab.
2. Upload an image to remove all metadata.
3. Download the metadata-free image.

### 6. Convert Images to JPEG
1. Switch to the **Images to JPEG** tab.
2. Upload images in any format.
3. Click **Convert to JPEG** to process the files.
4. Download individual files or all files as a ZIP archive.

## Technical Details

### Technologies Used
- **Tailwind CSS**: For modern and responsive design.
- **JSZip**: For creating downloadable ZIP archives.
- **piexif.js**: For reading, writing, and modifying EXIF metadata.
- **Gemini API**: For AI-powered metadata generation.

### Compatibility
- Supports JPEG, PNG, and other common image formats for metadata reading and conversion.
- Converts non-JPEG images to JPEG for uniformity and compatibility.

## Development Notes
Feel free to fork or modify this project. Contributions are welcome for enhancements such as support for additional image formats or metadata fields.

## Acknowledgments
This tool was created with the intent to simplify image metadata management while maintaining high performance and user-friendly design.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute as needed.

## Author
**Glyphiez**
