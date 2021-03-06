![Streamtool](https://github.com/micky4966/streamtool/raw/master/app/www/img/streamtool.png "Streamtool")

A web software for managing and manipulating video streams.

## Features:
- Streaming and restreaming
- Manage users
- Manage stream categories
- Manage streams 
- Transcode streams with advanced configuration
- Manage transcode profiles
- NVENC full hardware transcoding (decoding/encoding) support for H264/HEVC
- Autorestart on stream failure
- Playlist generation
- Bulk import
- User Agent manager
- IP filter manager
- Resources monitor
- Remove nvidia encoder limit on demand
... and more to come
 
## Installation
 **SUPPORTED DISTRIBUTION : Ubuntu 20.04 64 BIT**
  As administrator execute:
```bash
curl -s https://raw.githubusercontent.com/micky4966/streamtool/master/install/st-11.20.sh | sudo bash
```
  Visit : http://streamtool-adress:9001/ login with 
 Default Username Password: admin


## How does it work ?
- Default login: admin / admin
  - Add a category to allow user and stream creation
  - Add a stream or import a playlist
  - Add a user
- not recommanded to change hls output directory
- Not using transcoding will only remux stream to simple hls output.
- vaapi soon to be implemented


