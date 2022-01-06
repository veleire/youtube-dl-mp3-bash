# youtube-dl-mp3-bash
Simple bash script to download mp3 from youtube including embedded thumbnails

### Prerequisites

Require ffmpeg and youtube-dl

* youtube-dl
```sh
sudo curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
```
  
```sh
chmod a+rx /usr/local/bin/youtube-dl
```
  
* ffmpeg

**Debian / Ubuntu Linux**  
```sh
apt install ffmpeg
```

**Arch Linux**  
```
pacman -S ffmpeg
```

### Installation

Download script
   ```sh
sudo curl -L https://github.com/veleire/youtube-dl-mp3-bash/raw/main/yt -o /usr/local/bin/yt
   ```

   ```sh
sudo chmod a+rx /usr/local/bin/yt
   ```
## Usage

 ```sh
yt https://www.youtube.com/watch?v=id
```

**note:** The utility will save all downloaded files in ``` ~/mp3```. 
