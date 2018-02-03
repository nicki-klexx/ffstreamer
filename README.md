# ffstreamer
This is a tool for streaming video files to a remote server using ffmpeg.

## Usage

````
ffstreamer <VIDEO FILE> [OPTIONS]
````
````
Options:
	-c width:height:x:y  Croppes the Video to specified values.
	-s timestamp         Timestamp where the Video starts. You can specify
	                     it in seconds or e.g. in hh:mm:ss.
	-p                   Makes your stream more private by adding a random
	                     to the stream url.
````
On your first run you are also asked for the server address you want to stream to and can set other options to your config.
