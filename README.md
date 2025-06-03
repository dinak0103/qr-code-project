# 📷 QR Code Generator CLI

A simple Node.js command-line application that generates a QR code image from a user-provided URL and saves both the QR code and the URL to your local filesystem.

## 🚀 Features

- Prompts the user to input a URL
- Generates a QR code using the `qr-image` package
- Saves the QR code as a PNG file (`qr_img.png`)
- Saves the entered URL to a text file (`URL.txt`)

## 🛠️ Technologies Used

- [Node.js](https://nodejs.org/)
- [Inquirer](https://www.npmjs.com/package/inquirer) — for interactive CLI prompts
- [qr-image](https://www.npmjs.com/package/qr-image) — to generate QR codes
- [fs (File System)](https://nodejs.org/api/fs.html) — to handle file writing

## 📦 Installation

```bash
git clone https://github.com/your-username/qr-code-project.git
cd qr-code-project
npm install
```
## 🧪 Usage

Run the project with:

```bash
node index.js
```
