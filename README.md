send_h264file_by_rtp
====================

send h264 file by rtp via udp

test:

```console
$ make
$ make test

$ # cvlc test.sdp &  # or mplayer(or ffplay) test.sdp &
$ # ./send_h264file_rtp record.h264 127.0.0.1 1234
$ # ffmpeg -i xx -f h264 - | ./send_h264file_rtp - 127.0.0.1 1234
```

