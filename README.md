# Youpload
NodeJS Youtube Upload App with OAuth2.0 

To run: 
1) enter your own Client ID and Client Secret
2) replace the file where you create the readable stream to upload the video you wish to 
  media: {
                body: fs.createReadStream("your file path")
            }
            
3) in the terminal: node upload.js
4) authorise the app in the browser and check the video on your YouTube account
