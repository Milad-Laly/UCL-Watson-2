# Prerequisites
The first step would be to create a Spotify account. It wouldn't need to be a premium account for creating a playlist. However, for somethings such as playing a playlist or pausing music it would need to be a premium account.

Also, it would be to install node.js on your system. You won't need to code in  JavaScript.  This is only to authorize your spotify account to be controlled by Watson Assistant.

https://nodejs.org/en/download
https://radixweb.com/blog/installing-npm-and-nodejs-on-windows-and-mac

# Step 1

Once you are logged in Spotify and have Node.JS installed. Go to your terminal or CMD and from the folder Session_2_3. Follow the path: web-api-examples > authentication > authorization_code. 

Type in "node app.js" and press enter to launch to create the Spotify Access Token.

Proceed to go to localhost:8888 in your browser. It should either say Log in with Spotify or should automatically come with a page saying authorize.

Afterwards, you will have an access token. Double click on the access token to copy it and you can paste it later as shown in the recorded video.

## Step 2

After having everything setup with Spotify, log in into IBM Cloud and access the Watson Assistant instance. 

In the Session_2_3 file, there is a file  called 'test.json' this will include the minimum 'instructions' to tell Watson how to use Spotify API to create a playlist.

As shown in the video, go to extensions and click build custom  extension. Follows the steps and paste the access token in step 1. 


## Step 3
Follow the video on how to create an action and use the extension. 

Do make sure to run 'Get User Profile' first as this would get the unique ID for the account so Spotify will know that you are creating an playlist for this account.

After, use the 'Create a Playlist' extension and follow the video.

After running the action, you should be able to see the playlist you create and a link showing you it has been created.


If you do have any errors or questions, do feel free to message the Teams groupchat. 


