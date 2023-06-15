# Socket-Video-Streaming
Socket programming to send and receive webcam video
## What is socket?
A socket is a software abstraction that allows communication between two computers over a network. It provides an interface for programs to send and receive data across a network or between processes on the same machine.

In the context of computer networking, a socket is identified by an IP address and a port number, which together uniquely identify a specific endpoint of communication. The combination of IP address and port number on a system is often referred to as a socket address.

Sockets can be used in various network protocols, such as TCP (Transmission Control Protocol) or UDP (User Datagram Protocol), to establish a connection and exchange data between client and server applications.

<img src="https://github.com/Qyt0109/Socket-Video-Streaming/blob/main/SocketWebcam/Images/socket.png">

A socket can be either a client or a server. The client socket initiates a connection to a server socket, and the server socket listens for incoming connections from client sockets. Once a connection is established, both the client and server sockets can send and receive data.

In programming, sockets are typically implemented through socket libraries or APIs provided by the operating system. These libraries provide functions and methods to create, configure, and manage sockets, as well as send and receive data over the network.

Overall, sockets form the foundation of network communication, enabling applications to communicate and exchange data in a networked environment.

## How to run the code

### Step 1: Open SocketWebCam folder (VSCode)
<img src="https://github.com/Qyt0109/Socket-Video-Streaming/blob/main/SocketWebcam/Images/1.png">
There is 2 files:
<ul>
  <li><a href="https://github.com/Qyt0109/Socket-Video-Streaming/blob/main/SocketWebcam/server.py">server.py</a> - This code is for setting up a server that captures video frames from a webcam using OpenCV and sends them over a socket connection to a client</li>
  <li><a href="https://github.com/Qyt0109/Socket-Video-Streaming/blob/main/SocketWebcam/client.py">server.py</a> - This code represents the client-side implementation to receive and display video frames from the server</li>
</ul>

### Step 2: Run the server
<img src="https://github.com/Qyt0109/Socket-Video-Streaming/blob/main/SocketWebcam/Images/2.png">
Open Terminal and run $python3 server.py (Make sure you have already installed all necessary libraries like socket, cv2,... before run the server.py)

