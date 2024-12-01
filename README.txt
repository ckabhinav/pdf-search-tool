
# PDF Search Tool

**PDF Search Tool** is a simple and efficient application designed to help you search for specific text within multiple PDF documents at once. This tool is perfect for users who frequently need to search large collections of PDF files for specific information without opening each document manually.

## Features

- **Batch Search Across PDFs**: Quickly search for specific text in multiple PDF documents located in a folder.
- **Recursive Search**: Option to include subfolders in the search, ensuring that all files are covered.
- **Exact or Fuzzy Match**: You can choose between exact matches or fuzzy matches using stemming and similarity measures, making the search flexible and powerful.
- **Preview Snippets**: Provides a snippet of text from each page where the search term is found.
- **PDF Viewer Integration**: Opens specific pages of a PDF in your preferred viewer, making it easy to navigate to the exact section of interest.
- **File Caching**: Uses caching to improve the performance of repeated searches within the same collection of documents.
- **Clear Cache Option**: Ability to clear cache to ensure you are always working with the most up-to-date results.
- **Graphical User Interface (GUI)**: User-friendly interface built with Tkinter for ease of use.
- **Custom PDF Viewer**: Ability to set your own preferred PDF viewer application.

## How to Use

1. **Select a Folder**:
   - Click on the **"Browse"** button to select the folder containing the PDF files you wish to search.

2. **Set PDF Viewer** (Optional):
   - Enter the path to your preferred PDF viewer and click **"Set Viewer"**. This allows you to open specific pages directly from the results.

3. **Enter Search Term**:
   - Type the text you want to search for in the **"Search Term"** field.

4. **Choose Options**:
   - **Include Subfolders**: Tick the checkbox if you want to search within subfolders.
   - **Exact Match**: Tick this box if you want exact match results.

5. **Search**:
   - Click **"Search PDFs"** to start the search process. The results will display the file name, page number, and a snippet containing the search term.

6. **View Results**:
   - **Double-click** on a result to open the corresponding page in the PDF viewer.
   - **Right-click** to preview the selected page in a new window.

7. **Clear Cache**:
   - Click the **"Clear Cache"** button to clear stored search data.

## Installation

This tool is available as a standalone `.exe` file, meaning there is no need to install Python or any other dependencies. Just download the executable and run it on your Windows system.

### System Requirements

- **Operating System**: Windows (7/8/10/11)
- **Python Dependencies** (For Developers):
  - `fitz` (PyMuPDF)
  - `tkinter` (Standard with Python)
  - `Pillow` (PIL for image processing)
  - `nltk` (Natural Language Toolkit)
  - `fuzzywuzzy` (for fuzzy matching)
  - **Note**: The `.exe` includes these dependencies; only needed for development purposes.

## Development

For developers interested in contributing, please clone the repository and set up the environment using the requirements.txt file. Contributions are always welcome to improve the tool!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Issues

If you encounter any issues or have feature requests, feel free to raise an issue in the GitHub repository.

## Credits

This tool was developed by **Abhinav** with support for all the necessary functionalities to efficiently search through PDF collections.

---

**Note**: If your PDF viewer is not set, the default system PDF viewer will be used.
