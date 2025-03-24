# Internet Speed Test Web Application

This web application provides a simple and user-friendly interface to measure your internet connection's download speed, upload speed, ping (latency), and jitter.

## Features

* **Download Speed Test:** Measures the download speed in Mbps by downloading files of varying sizes.
* **Upload Speed Test:** Measures the upload speed in Mbps by uploading files to a test server.
* **Ping (Latency) Test:** Measures the round-trip time (latency) in milliseconds (ms).
* **Jitter Measurement:** Calculates and displays the variation in ping latency in milliseconds (ms).
* **Real-time Graph:** Visualizes download and upload speed progression using Chart.js.
* **Progress Bar:** Displays the progress of each test.
* **IP Address Display:** Shows the user's IP address.
* **Server Name Display:** Shows the server used for testing.
* **Responsive Design:** Works seamlessly on various devices (desktops, tablets, and mobile phones).
* **User-Friendly Interface:** Clean and intuitive design.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Chart.js (for graph visualization)

## How to Run Locally

1.  **Clone or download the repository:**
    ```bash
    git clone [repository URL]
    ```
    or download the zip file and extract it.
2.  **Open `speedtest.html` in your web browser:**
    * Navigate to the directory where you saved `speedtest.html`.
    * Double-click the file to open it in your default browser.
    * Or, open your browser and press `Ctrl + O` (Windows/Linux) or `Cmd + O` (macOS) and select the `speedtest.html` file.

3.  **Click the "Start Speed Test" button:**
    * The application will begin testing your internet connection.
    * The results will be displayed on the page.

## Important Notes

* **Internet Connection:** An active internet connection is required for the speed test to function.
* **Browser Compatibility:** The application should work in most modern web browsers.
* **Server Reliability:** The accuracy of the test depends on the reliability of the test servers.
* **Accuracy:** Internet speed tests provide estimates and might not always be perfectly accurate.
* **CORS:** If you host this code on a server, you may encounter CORS errors due to cross-origin requests. Ensure your server is configured to handle CORS requests correctly.
* **Ping Test:** The ping test is done via HTTP request and may not be as accurate as an ICMP ping.
* **IP address:** The IP address is fetched using an external API.

## Future Enhancements

* Store and display historical test results.
* Provide options for sharing test results.
* Offer advanced settings for customizing the test parameters.
* Provide information about the user's ISP and location.
* Implement a map showing server locations.
* Add more robust error handling.
* Add unit and integration tests.
* Improve ping test accuracy.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
