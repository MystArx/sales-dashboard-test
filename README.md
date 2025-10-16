git clone https://github.com/your-username/sales-dashboard-test.git
    cd sales-dashboard-test
    ```
    Otherwise, ensure you have all project files (e.g., `index.html`, `script.js`, `style.css`, `data.csv`) in a single directory.

2.  **Ensure `data.csv` is present:**
    Make sure the `data.csv` file (containing your sales data) is located in the root directory of the project, alongside `index.html` and any associated JavaScript/CSS files. The application expects this file to be present for data fetching.

3.  **Open `index.html` in a web browser:**
    Simply open the `index.html` file in your preferred web browser. You can do this by navigating to the file in your file explorer and double-clicking it, or by using a local development server (e.g., `python -m http.server` for Python users, or a similar tool for other environments) for better handling of file paths and security.

4.  **Interact with the dashboard:**
    *   Upon loading, the total sales amount, calculated from the `data.csv` file, will be displayed prominently within the `<h1 id="total-sales">` element.
    *   Locate the **dark mode toggle button** in the top-right corner of the page. Click this button to switch between the default light theme and the new dark theme. The page's background and text colors will adjust accordingly.

## License

This project is open-sourced under the MIT License.

```
MIT License

Copyright (c) [Year] [Your Name or Organization]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.