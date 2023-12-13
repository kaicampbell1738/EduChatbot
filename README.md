# EduChatbot
Prerequisites

Before you begin, ensure you have the following installed on your system:

    Node.js (at least version 12)
    npm (usually comes with Node.js)
    Git (for version control)

## Setting Up the Server

Navigate to the server directory from the root of the project:

    cd server

### Install the necessary packages using npm:

    npm install

## Starting the Server

Once the dependencies are installed, you can start the server with:

    node index.js

The server should now be running on http://localhost:4000 (or the port you specified in your .env file).

## Setting Up the Client

Open a new terminal tab or window, navigate back to the root directory of your project, and then to the client directory:

    cd ../client

### Install the necessary packages using npm:

    npm install

## Starting the Client

Once the dependencies are installed, you can start the client with:

    npm start

### This should open the chat application in your default web browser. If it doesn't, you can manually navigate to http://localhost:3000 in your browser.

## Using the Application

Make sure both client and server is running. You only need one client instance running. Just open multiple tabs if you wish to use multiple clients. Enter a username on the client's login screen to start chatting.

# Connecting from other machines on the same network

Change `SERVER_URL` in `client/src/App.tsx` to your machine's local ip address.

[For mac]([url](https://www.security.org/vpn/find-mac-ip-address/)https://www.security.org/vpn/find-mac-ip-address/)
[For windows]([url](https://support.microsoft.com/en-us/windows/find-your-ip-address-in-windows-f21a9bbc-c582-55cd-35e0-73431160a1b9)https://support.microsoft.com/en-us/windows/find-your-ip-address-in-windows-f21a9bbc-c582-55cd-35e0-73431160a1b9)
    

