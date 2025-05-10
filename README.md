# Project Introduction
This is a music player application developed based on wechat mini-programs, imitating the mini-programs of NetEase Cloud Music, providing users with a convenient and personalized music experience platform. It integrates multiple functions such as music playback, personalized recommendation, playlist management, search, comments and sharing.
Main functions:
Music playback: Supports playing, pausing and switching songs, real-time display of lyrics, and adjustment of playback progress.
Personalized recommendation: Based on the user's listening history and preferences, suitable songs, playlists and radio programs are recommended.
Playlist management: Users can create, edit and share their own playlists, add or delete songs.
Search function: Supports multi-type search (songs, singers, albums, etc.), saves search history, and provides intelligent prompts.
User interaction: Users can comment on songs, playlists, MVS, etc., like and collect their favorite content.
<!--by Lxd -->


<!-- by Meng YiXin -->
# Project Installation

### (1) Clone the Project

a. Main Project
```bash
git clone https://github.com/TMyxGames/NeteaseMusicWxMiniApp.git
```

b. Backend Project
```bash
git clone https://github.com/TMyxGames/netmusic-node.git
```

### (2) Install Node.js

a. Download Address:https://nodejs.org/en/

b. Check Installation
```bash
node -v
```

### (3) Launch the Backend Project

a. Open the terminal and switch the working path to the backend project folder

b. Enter
```bash
npm i
node app.js
```
### (4) Open the Main Project

In ```Details > Local Settings```, choose ```Do not verify legal domain, web-view (business domain), TLS version, and HTTPS certificate```

### (5) Compile the Project

# Main Features and Screenshots of the Project

<!-- by Meng Yixin -->
### album

![picture](picture/QQ20250510-034959.jpg)
The core functionality of the music player, including obtaining music information, playback control, sharing, and page navigation.

● index.js
    Defines the data structure and methods, implementing the functionality of the music playback page.
● index.wxml
    Implements the appearance of the music playback page.
● index.wxss
    Defines the component styles of the music playback interface.

### artist

![picture](picture/QQ20250510-041120.jpg)

The artist details page functionality, including artist information, works, albums, and music videos (MVs).

● index.js
    Defines the data structure and methods, implementing the functionality of the artist details page.
● index.wxml
    Implements the appearance of the artist details page.
● index.wxss
    Defines the component styles of the artist details page.

### cloud
The cloud disk functionality, used to display the list of music stored in the user's cloud disk.

● index.js
    Defines the data structure and methods, implementing the cloud disk functionality.
● index.wxml
    Implements the appearance of the cloud disk page.
● index.wxss
    Defines the component styles of the cloud disk page.

### djradio

![picture](picture/QQ20250510-182955.jpg)

The radio station details page functionality, including radio station information, program list, and playback control.

● index.js
    Defines the data structure and methods, implementing the operational logic of the radio station details page.
● index.wxml
    Implements the appearance of the radio station details page.
● index.wxss
    Defines the component styles of the radio station details page.

### fm

![picture](picture/QQ20250510-183203.jpg)

The private FM functionality, supporting song recommendations based on user preferences and playback control.

● index.js
    Defines the data structure and methods, implementing the operational logic of the private FM playback page.
● index.wxml
    Implements the appearance of the private FM playback page.
● index.wxss
    Defines the component styles of the private FM playback page.


