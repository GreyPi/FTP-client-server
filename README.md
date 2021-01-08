# Class Project

**Contributers:**
  maburdi94,
  GreyPi,
  nimapk
 
**Description:**

  This project implements a FTP server and a FTP client. The client can connect to
  the server and has access to upload and download files to and from the server. It uses two channels; control and data. The client
  initally connects to the control channel and is able to send and recieve data through the data channel. The channel is established
  and torn down after every file transfer for security on both ends. We designed a protocol on how data is sent and recieved to
  ensure no data was lost and to avoid any overflows. A good learning project in understanding computer networking.

**How to Run:**
  1. Download Zip folder.
  2. Extract files.
  3. Open terminal/CMD in directory for server.py and client.py.
  4. In server.py run "python server.py" The server is now running and listening for requests.
  5. In client.py run "python client.py 3000" to establish connection.    
  6. Any data sent to the server will now be displayed.
  
***Sources***: Professor Yun Tian of Cal State Fullerton University.
