# Touch Server
New type of web server for developers.
## How can you doing
Web hosting on localhost is available.
You can freely decide the port number and the directory to host.
## Install
First, install Node.js.
If apt is available on Linux:
```$ sudo apt install node```
to install a fairly old Node.js.
On Windows or Mac, go to the official Node.js website, click on 14.17.5.LTS, open the downloaded executable file, and install as appropriate.

Download and unzip the file to any directory.

Once the mime-types installation is complete, the Touch Server installation is complete.
## Usage
It works by calling index.js from anywhere with the node command. The root directory is the current directory at the time of the call.
The argument is the port number. If no argument is specified, the port number is specified as 3000.
In my environment, the port number is set to at least 1024 because it was confirmed that it does not work properly unless the port number is at least 1024.

Example:
```$ node index.js 5500```
