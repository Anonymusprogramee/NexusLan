# NexusLAN

A lightweight LAN communication tool that works completely offline, without accounts, cloud services, or administrator permissions.

> The complete documentation and setup guide can be found inside the `.tar` file.
> This README contains a quick setup summary.

---

# Requirements

Before starting, make sure you have:

* Python installed
* `pip` working correctly
* All devices connected to the same LAN/WiFi network

---

# Installing Dependencies

Open a terminal inside the project folder and run:

```bash
pip install -r requirements.txt
```

This step is required for both the server and the clients.

---

# Setting Up the Server

Choose a computer or virtual machine that will act as the central server.

Requirements for the server:

* Must be connected to the same LAN network
* Must have Python and the required dependencies installed

To start the server, open a terminal inside the project folder and run:

```bash
python -m server
```

If everything is correct, the server will start and wait for incoming connections.

---

# Setting Up the Client

After installing the dependencies, start the client with:

```bash
python -m client
```

A graphical interface will appear.

To connect to the server:

1. Go to the **Connect** section (bottom-left corner)
2. Enter your username
3. Enter the server IP address
4. Press connect

Once connected, you will be able to:

* Chat with other users in real time
* Send files through the LAN
* View connected users
* Use NexusLAN features without internet access

---

# Notes

* All communication stays inside the local network
* No external servers or cloud services are used
* Data is stored locally using SQLite
* Received files are saved in the user's Downloads folder

---

# Thank You

Thank you for using **NexusLAN**.
