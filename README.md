# youtube-dl-mp3-bash
Simple bash script to download mp3 from youtube



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

```sh
apt install ffmpeg
```

### Installation

Download script
   ```sh
sudo curl -L https://github.com/veleire/youtube-dl-mp3-bash/raw/main/yt -o /usr/local/bin/yt
   ```

   ```sh
chmod a+rx /usr/local/bin/yt
   ```
## Usage

 ```sh
yt https://www.youtube.com/watch?v=id
```

Your download directory is ~/mp3
