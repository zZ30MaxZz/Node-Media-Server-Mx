mxstream
1691635647
secret-0: mxsecret2023
secret-1: mxsecret2023render

/live/mxstream-1691635647-mxsecret2023
/live/mxstream-1691635647-mxsecret2023render

generated
from

md5("/live/mxstream-1691635647-mxsecret2023”)

md5-0: 3f0149c24f33839f713c1509fb5e7b4a
md5-1: c0993b30746786d26447dd7974c98e85


rtmp://localhost/live

key-0: mxstream?sign=1691635647-3f0149c24f33839f713c1509fb5e7b4a
key-1: mxstream?sign=1691635647-c0993b30746786d26447dd7974c98e85


> live 

http://localhost:8000/live/mxstream.flv

rtmp://localhost/live/mxstream ✔️✅

rtmp://localhost/live/mxstream?sign=1691635647-3f0149c24f33839f713c1509fb5e7b4a

http://localhost:8000/live/mxstream/index.m3u8

ws://localhost:8000/live/mxstream.flv?sign=1691635647-3f0149c24f33839f713c1509fb5e7b4a

### Render
https://mxbroadcast.onrender.com

> Broadcast
url: rtmp://mxbroadcast.onrender.com/live
key: mxstream?sign=1691635647-c0993b30746786d26447dd7974c98e85

https://mxbroadcast.onrender.com/live

live
rtmp://mxbroadcast.onrender.com/live/mxstream




### Docker

> Local

docker build -t broadcast:1 .

docker run --name nms -d -p 1935:1935 -p 8000:8000 -p 8443:8443 broadcast:1

> Image illuspas

docker run --name nms -d -p 1935:1935 -p 8000:8000 -p 8443:8443 illuspas/node-media-server