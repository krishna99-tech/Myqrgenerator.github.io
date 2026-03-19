# MyQRGenerator.github.io

This project is a simple web-based WiFi QR Code Generator that allows users to generate a QR code for their WiFi network. By entering the WiFi credentials, a QR code is created which can be scanned by any smartphone to connect instantly without manually typing the password.

The main purpose of this project is to provide an easy and quick way to share WiFi access securely and conveniently. It is especially useful in homes, offices, cafes, and public places.

To use the application, open the webpage and enter the required WiFi details such as network name (SSID), password, and security type (WPA/WPA2, WEP, or open network). Once the details are entered, the application generates a QR code automatically. Users can then scan the QR code using their mobile device to connect to the WiFi network.

The QR code follows the standard WiFi format:
WIFI:T:<encryption>;S:<ssid>;P:<password>;H:<hidden>;

Example:
WIFI:T:WPA;S:MyWiFi;P:12345678;;

This project is built using basic web technologies including HTML, CSS, and JavaScript. It runs entirely in the browser and does not require any backend or server, making it fast, lightweight, and easy to deploy using GitHub Pages.

To run the project locally, clone the repository and open the index.html file in your browser:
git clone https://github.com/krishna99-tech/Myqrgenerator.github.io.git
cd Myqrgenerator.github.io

Then simply open index.html in any browser.

This project can be used for quick WiFi sharing, generating printable QR codes, or integrating into other web applications.

Future improvements may include saving QR codes as images, adding customization options (colors, logos), and supporting additional QR data types.

This project is open-source and available under the MIT License.
