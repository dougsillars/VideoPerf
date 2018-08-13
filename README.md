# VideoPerf
Studying different ways to serve video to study the performance aspects of video delivery.

The base video is served from index.html, and the other pages are modifications of the original video.

The video is a 38s clip of Big Buck Bunny.
38s, 98.1MB, 20.5 MBPS, mov,mp4,m4a,3gp,3g2,mj2

<h1>Compare http vs https</h1>
<b>https.html</b> has the same video, but uses HTTPS to serve the video.

In 9 runs:
index.html has a median load time of 2.879s.  
https.html has a median load time of 4.291s.

data:
https://www.webpagetest.org/result/180813_ZA_d459cbb671138352a8060341363f8c1c/
https://www.webpagetest.org/result/180813_8D_3cbf82f46b37058fd2ea92cbc1c8a16a/

<h1>Compare various bitrates</h1>
index.html 		20 MBPS
index10.html 	10 MBPS
index5.html		5  MBPS
index2.html		2 MBPS
index1.html		1 MBPS
