exec_static /usr/local/bin/./ffmpeg -i udp://@233.1.15.7:1234 -preset ultrafast -profile:v main -level 4.0 -c:v libx264 -vf yadif=0:-1:0 -c:a aac -f flv rtmp://127.0.0.1/cam1/stream;
        
exec_static /usr/local/bin/./ffmpeg -i udp://@233.1.21.31:1234 -preset ultrafast -profile:v main -level 4.0 -c:v libx264 -vf yadif=0:-1:0 -c:a aac -f flv rtmp://127.0.0.1/cam1/stream2131;
