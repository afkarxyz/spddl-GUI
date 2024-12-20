[![GitHub All Releases](https://img.shields.io/github/downloads/afkarxyz/SpotifyDown-GUI/total?style=for-the-badge)](https://github.com/afkarxyz/SpotifyDown-GUI/releases)

**SpotifyDown GUI** is a graphical user interface for downloading Spotify tracks, albums, and playlists directly from Spotify using an API created by SpotifyDown.com

### [Download](https://github.com/afkarxyz/SpotifyDown-GUI/releases/download/SpotifyDown/SpotifyDown.exe)

## Screenshots

![image](https://github.com/user-attachments/assets/f1fb5a71-6e81-48de-9c1c-718fb936a023)

![image](https://github.com/user-attachments/assets/ac85475b-746a-4eae-93fc-ec3b5606191e)

![image](https://github.com/user-attachments/assets/7ddf6be4-b24a-45cc-ae74-ee6a5d5adbd4)

## Features

- Download individual tracks, entire albums, or playlists from Spotify
- High-quality audio download at `320 kbps` for the best listening experience
- The ability to download more than 100 tracks
- No Spotify account required

## Usage

> [!IMPORTANT]  
> Due to updates in the API, a token is required periodically. Follow the steps below to obtain the token.

1. Visit [https://spotifydown.com/](https://spotifydown.com/) and open the **Network** tab in your browser's developer tools (press `F12`).  
2. While the Network tab is open, press the download button.  
3. Filter the requests to display only **Fetch/XHR**, then look for `{track_id}?token=` and click on it.  
4. Open the **Payload** tab.
   
![image](https://github.com/user-attachments/assets/00448018-482f-4b19-b143-7b4ee8d9bca9)

5. Copy the token value from the part that looks like this: `0.FPfLLqH4r-2fEehjOPHII57lSX5AVYsW...`
