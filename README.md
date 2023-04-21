# LCA (Lights-Camera-Action)
 The objective of this project is to create a web-based real-time synchronized media player that allows multiple users to watch and control the playback of a single media simultaneously. It is built using Flask and Socket.IO for the backend, and HTML, CSS, and JavaScript for the frontend.

# Installation
To install LCA, follow these steps:
 1. Clone the repository: git clone https://github.com/unisimplex/Lights-Camera-Action.git
 2. Install the required packages: pip install -r requirements.txt
 3. Run the application: python server.py

# Usage
To use LCA, follow these steps:
 1. Open your web browser and navigate to http://127.0.0.1:5000
 2. Copy and paste the YouTube video URL into the video player.
 3. Enjoy watching the video in sync with your friends!

# Public server 
The server.py file hosts the server in public mode , that means anyone in the same network can visit the website using the servers ip address. Below are the steps to do this 
 1. Open the Command Prompt by pressing the "Windows Key + R" and typing "cmd" in the Run dialog box. Click "OK" or press Enter to open the Command Prompt.
 2. Type "ipconfig" in the Command Prompt and press Enter. This command will display the network configuration details of your machine.
 3. Scroll down to the section labeled "Ethernet adapter" or "Wireless LAN adapter," depending on your network connection.
 4. Look for the line that says "IPv4 Address." This line will display your machine's IP address on the network.
 5. You can also find the IP address of other devices on the network by using the "ping" command followed by the device's hostname or IP address. For example, type "ping google.com" to find the IP address of Google's server.
 6. Once you have found the IP address, anyone *in the same network* can use it to access the website by visiting (http://ip_found:5000)



# Known Issues
There is an module version issue with the youtube-dl module that sometimes causes the video to fail to load. We are working on a fix for this issue.

# Contributing
We welcome contributions from anyone interested in improving LCA. To contribute, please fork the repository and submit a pull request.

# Contact
If you have any questions or comments about LCA, please contact us at Unisimplex@gmail.com 




