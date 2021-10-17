# streaming

## apis

- WebRTC
  - getUserMedia()
  - navigator.mediaDevices.getUserMedia()
  - webcam -> MediaStream
  - constraints API
  - select media source
    - navigator.mediaDevices.enumerateDevices()
  - https://webrtc.org/getting-started/media-devices
  - https://webrtc.github.io/samples/


- Apple HLS
  - HTTP Live streaming
    - https://developer.apple.com/streaming/
    - HTTP Live Stream Server Webpage
      - Host: Web server or CDN
      - Receiver: HTML page for browsers or client app
      - encode your source material or live streams as fragmented MPEG-4 media files containing HEVC or H.264 video and AAC or AC-3 audio
      - https://developer.apple.com/documentation/http_live_streaming/deploying_a_basic_http_live_stream
        - HTML page
          - HTML5 <video> tag
          - M3U8 playlist file as the video source



  - Streaming examples
    - .M3U8 files
      - https://devstreaming-cdn.apple.com/videos/streaming/examples/img_bipbop_adv_example_ts/master.m3u8



## links

- https://www.html5rocks.com/en/tutorials/getusermedia/intro/
- https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia
- https://developer.mozilla.org/en-US/docs/Web/API/MediaStream
