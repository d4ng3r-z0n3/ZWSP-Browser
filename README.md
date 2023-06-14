# ZWSP Browser

ZWSP Browser is a simple web browser built using PyQt5 that allows you to browse web pages and detect and decode zero-width characters (ZWSP). ZWSP characters are invisible Unicode characters that can be used for various purposes, including steganography and data hiding.

## Features

- **Web browsing:** ZWSP Browser provides a user-friendly interface for browsing web pages. You can navigate backward and forward, reload pages, stop loading, and go to the home page.
- **URL navigation:** You can enter a URL in the address bar and press Enter to navigate to that web page.
- **Title update:** The browser window title is updated with the current page's title.
- **ZWSP detection and decoding:** ZWSP Browser can detect zero-width characters in the loaded web page's body text and decode them to reveal hidden messages.
- **HTML rendering:** Decoded messages are saved as HTML files and opened in the browser for easy viewing.
- **Windows executable (ZWSP-Browser.exe):** You can now run ZWSP Browser as a standalone Windows executable by simply double-clicking on `ZWSP-Browser.exe` Which with packed dependencies is to large to upload to GitHub. 

## Installation

To use ZWSP Browser, you need to have Python installed on your system. You also need to install the required dependencies by running the following command:

```
pip install pyqt5 pyqtwebengine
```

## Usage

To run ZWSP Browser, execute the following command:

```
python ZWSPBrowser.pyw
```

The browser window will open, and you can start browsing by entering URLs in the address bar or using the navigation buttons. To detect and decode ZWSP characters, simply load a web page containing hidden messages. The decoded messages will be saved as HTML files and opened in the browser for easy viewing.

## License

ZWSP Browser is open-source software licensed under the MIT license.

## Contribution

Contributions to ZWSP Browser are welcome! If you encounter any issues, have suggestions for improvements, or would like to contribute code, please feel free to open an issue or submit a pull request on the GitHub repository.

## Acknowledgements

ZWSP Browser was created by õÕ as a personal project. It builds upon the powerful features of the PyQt5 library and leverages the web browsing capabilities provided by the Qt WebEngine module.

## Contact

For any inquiries or questions regarding ZWSP Browser, please contact õÕ.

Happy browsing and decoding ZWSP characters!
