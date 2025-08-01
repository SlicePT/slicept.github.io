# slicept.github.io

This is the repository for the SlicePT website, which is hosted on GitHub Pages. The website is built using HTML and CSS, and it serves as a platform to showcase the PT to prospective clients.

## Running the Webpage Locally

To view the website on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/slicept/slicept.github.io.git
    ```
2. Navigate to the project directory:
    ```bash
    cd slicept.github.io
    ```

### Option 1: Open Directly
3. Open the `index.html` file in your web browser.

No additional setup is required since the site uses only HTML and CSS.

### Option 2: Run a Local Web Server (Recommended for Testing)
If you want to test features like navigation, relative paths, or preview the site as it would appear when hosted, you can run a simple local web server:

#### Using Python (if installed)
```bash
python3 -m http.server 8000
```
Then open [http://localhost:8000](http://localhost:8000) in your browser.

#### Using Node.js (if installed)
First, install http-server globally (if not already installed):
```bash
npm install -g http-server
```
Then run:
```bash
http-server -p 8000
```
Open [http://localhost:8000](http://localhost:8000) in your browser.

---

## Requirements
- No dependencies required for basic usage.
- For local server testing, you need either Python 3 or Node.js installed.

## Troubleshooting
- If you see broken links or missing images, try running a local server as described above.
- For any issues, please open an issue in this repository.

## License
This project is licensed under the MIT License.