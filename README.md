# EasyPDF (PDF Generator with GPT-3.5 and Unsplash Image Integration)

This project utilizes various technologies to generate PDFs with text content generated by OpenAI's GPT-3.5 model and images fetched from Unsplash API. The main functionality involves creating a PDF document based on user-provided topics, with both textual content and relevant images.

## Technologies Used

- **Python**: The primary programming language used for development.
- **Pipenv**: Dependency management tool for Python projects.
- **OpenAI API**: Integrates GPT-3.5 for generating text content.
- **Unsplash API**: Used to fetch high-quality images based on provided topics.
- **Pillow (PIL)**: Python Imaging Library used for image processing.
- **FPDF**: Python library for creating PDFs.
- **Requests**: HTTP library for making API requests.
- **JSON**: For handling JSON data.
- **io**: Provides core tools for working with streams.
- **Time**: Used for delaying image placement in PDFs.

## Project Overview

The main functionality of the project involves generating PDF documents based on user-specified topics. The process involves two primary components:

1. **Text Content Generation**: The `content_generator` function uses OpenAI's GPT-3.5 model to generate descriptive text content based on a provided prompt. This content is generated in response to a prompt related to the topic provided by the user.

2. **Image Generation and PDF Creation**: The `pdf_generator` function orchestrates the process of generating text content, creating a table of contents, fetching relevant images from Unsplash based on the topics, and integrating both text and images into a PDF document.

## Usage

1. **Setup Environment**: Ensure you have Python and Pipenv installed on your system. Clone the repository and navigate to the project directory.

2. **Install Dependencies**: Run `pipenv install` to install project dependencies.

3. **Obtain API Keys**: Obtain API keys for OpenAI and Unsplash, and store them securely. Replace placeholders in the `keys.py` file with your actual API keys.


## File Structure

- **main.py**: Main script orchestrating the PDF generation process.
- **image_generator.py**: Module responsible for fetching images from Unsplash API.
- **keys.py**: Placeholder file for storing API keys (Ensure not to expose API keys in version control).
- **README.md**: This file documenting the project overview, usage instructions, and technologies used.


### Usage

Run the program using `python main.py`.

## Contribution

Contributions are welcome! If you'd like to enhance this project, feel free to fork the repository and submit pull requests with your changes. Here are some areas where you can contribute:

- Optimization of image resizing and placement algorithms.
- Error handling and exception management improvements.
- Refactoring for better code modularity and readability.
- Adding new features or integrations to enhance functionality.

Please ensure to follow the project's coding conventions and guidelines. Additionally, make sure to test your changes thoroughly before submitting a pull request. Thank you for your contributions!
