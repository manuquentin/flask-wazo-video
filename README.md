# flask-wazo-video

This is a simple web-based video conferencing application using Flask and Wazo Platform.

![Screenshot](screenshot.jpg)

## Installation Instructions

To install the application on your system follow these steps:

1. [Install Wazo Platform](www.wazo-platform.org) It's free software!
2. Create an account.
3. Clone this repository
4. Create a virtualenv and install the requirements
5. Create a *.env* file by copying the *.env.template* file. Fill out the values for your Wazo server, username, password and room.
6. Execute `python3 app.py` to start the server.
7. Navigate to *http://localhost:5000* on your web browser (or use your system's public IP address to connect from another computer or phone).
