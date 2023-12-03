# QR Code Generator Readme

This simple command-line tool enables users to generate QR codes for specified URLs. The project utilizes the `inquirer` library for user input, `qr-image` for QR code creation, and `fs` for file system operations.

## Installation

Ensure you have Node.js installed on your machine before running the project. You can download it from [https://nodejs.org/](https://nodejs.org/).

Follow these steps to set up and run the project:

1. Clone the repository to your local machine:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd qr-code-generator
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

To use the QR code generator, execute the following command in your terminal:

```bash
node index.js
```
This command will prompt you to enter a URL. After inputting the URL, the program will generate a QR code image (qr_image.png) and save it in the project directory.
Additionally, the entered URL will be saved in a text file (URL.txt).

## Dependencies
inquirer: Used for interactive command-line user interfaces. More information can be found here.

qr-image: Used for generating QR code images. More information can be found here.

fs: Node.js module for file system operations. More information can be found here.

### Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Ensure you follow the existing coding style and provide appropriate comments for clarity.
