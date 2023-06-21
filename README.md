# m3tv
<img src="https://i.imgur.com/Wg3AGFG.png" width=25% height=25%>
m3tv is a web app that allows you to stream M3U playlists and M3U8 streams. 

## Features

- Stream M3U playlists and M3U8 streams.
- Change background music, channel and sound effect volume
- Simple user interface
- adding/removing playlists and channels
- Support for 8 different languages (en, es, fr, gr, ar, ru, ch, jp)

## Screenshots
<img src="https://i.imgur.com/P0ic1Uv.png" width=50% height=50%>
<img src="https://i.imgur.com/6G3352P.png" width=50% height=50%>
<img src="https://i.imgur.com/J2hqipj.png" width=50% height=50%>
<img src="https://i.imgur.com/KyiQjC6.png" width=50% height=50%>


## Usage
App is available at https://m3tv.netlify.app/ and https://m3tv.vercel.app/ , make sure to click anywhere on the splash screen to enter the main menu.<br>
<br>
The second link uses a proxy server to access CORS restricted streams. <br>
You can use the first link combined with an extension to bypass CORS (like [Moesif Origin & CORS Changer](https://chrome.google.com/webstore/detail/moesif-origin-cors-change/digfbfaphojjndkpccljibejjbppifbc?hl=en), [Cross Domain - CORS](https://chrome.google.com/webstore/detail/cross-domain-cors/mjhpgnbimicffchbodmgfnemoghjakai?hl=en) and [Allow CORS](https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf?hl=en)) to access the same streams. <br>
Also, the first link doesn't automatically upgrade insecure requests, this is useful for when you're trying to view a playlist that's locally hosted using something like [dizquetv](https://github.com/vexorian/dizquetv) or [ErsatzTV](https://github.com/jasongdove/ErsatzTV). Just remember to allow insecure content. <br>

NOTE: On Microsoft Edge, you have to whitelist it by going to Settings > Cookies and site permissions > Manage and delete cookies and site data, then clicking "Add" in the "Allow" section and entering the URL

### Add Playlist or Channel
1. Click anywhere to exit the splash screen and enter the main menu
2. To add a playlist, click the "Add Playlists" button in the main menu, or the "Add Channels" button if your adding a channel
3. Enter the correct URL for the m3u playlist or m3u8 stream, if the m3u file is stored locally on your computer, click the "local" button NOTE: if you are adding a local playlist, you do not have to enter anything into the textbox. You will be prompted with a file dialog upon clicking the "Okay" button
4. Enter a title and an image URL for the logo (optional)
5. Press back to save changes
6. Once the playlist or channel is added, you can see view them by clicking the "Play Playlists" or "Play Channels" button in the main menu

### Background music
To change the background music: 
1. Find a youtube video
2. Click "share"
3. Click "Embed"
4. Copy the string that's in the quotations after "src=" and paste it into the text box
5. Click "Back" to save changes

### Controls
Next Channel - N<br>
Previous Channel - P<br>
Random Channel - R<br>
Save Channel - F (only available when watching a channel that's a part of a playlist)<br>
Next Page - D<br>
Previous Page - A

## Acknowledgements

- [hls.js](https://github.com/video-dev/hls.js/): Library for streaming.
- [m3u8-file-parser](https://github.com/NimitzDEV/m3u8-file-parser): A powerful parser for m3u and m3u8 files.
- [js-dos](https://js-dos.com/): simple API to run DOS games in browser.

