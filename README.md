# File-Server
Be able to access the contents of your computer on any device, anywhere. 

### Before usage:

Put your filepath into *File_server.js*
I'd put the filepath as your homefolder, but if you want to limit how much you can see on the
server just put the file path as any directory and you'll only be able to see whats in that directory.

### Usage:

`cd ThisFoldersFilePath`   
`npm install`   
`node File_server.js`

In your web browser go to: http://localhost:8080/   
To be able to view it using another device download a tunneling platform of your choosing.
I recomend [Ngrok](https://ngrok.com/)

Whith Ngrok downloaded use this command: `./ngrok http 8080`


Note, you can only view and download contents on the server. You cannot upload...for now...
