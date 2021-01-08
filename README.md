# Class Project
This project was worked with user maburdi94. This project implements a FTP server and a FTP client. The client can connect to
the server and has access to upload and download files to and from the server. It uses two channels; control and data. The client
initally connects to the control channel and is able to send and recieve data through the data channel. The channel is established
and torn down after every file transfer for security on both ends. We designed a protocol on how data is sent and recieved to
ensure no data was lost and to avoid any overflows. A good learning project in understanding computer networking.
