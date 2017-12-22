##lame (mp3/wav 转码与压缩神器)
>官方地址：http://lame.sourceforge.net

###安装说明
>cd source  
>./configure --enable-mp3x  --prefix=/app/lame  
>make &&make install
###使用手册
>动态码率  

./lame -h -v -b 112 -V 9 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-0kbs.mp3  
>平均码率  

./lame -h --abr 32 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-32kbs.mp3  
./lame -h --abr 16 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-16kbs.mp3  
./lame -h --abr 8 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-8kbs.mp3  
./lame -h --abr 4 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-4kbs.mp3  
./lame -h --abr 2 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-2kbs.mp3  
./lame -h --abr 1 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-1kbs.mp3  
./lame -h --abr 8 /app/lame/audio/audiosource-128kbs.mp3  /app/lame/audio/new/audiosource-8kbs.wav  
>更多说明  

访问https://www.muziflower.pub
