# VideoPerf
Studying different ways to serve video to study the performance aspects of video delivery.  Let's begin by modifying both the bitrate and the width of the video.

To do this, use the indexparam.html, and add width and br parameters to the url:

indexparam.html?width=960&br=1000 will give bitrate 1MBPS and width of 960.

The base video is a 38s clip of Big Buck Bunny.

38s, 98.1MB, 20.5 MBPS, mov,mp4,m4a,3gp,3g2,mj2

We can now run tests for this video at varying bitrates and widths with webpagetest to see how they load.