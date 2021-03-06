## About 

Based on [Hyperion NG](https://github.com/hyperion-project/hyperion.ng) with some performance tweaks especially for MJPEG/YUV grabbers with support for HDR/BT2020 using LUT tables.<br/>
Single and multi-threaded optimization (Rpi2/3/4) for USB v4l2 grabber.

## Download packages & sources

https://github.com/awawa-dev/HyperHDR/releases

You can use prepared SD card images just like Hyperbian.<br/>
Default hostname for SD images is HyperHDR so connect to http://hyperhdr:8090/<br/>
SSH is enabled on default. Default LUT table is already included!

### New features of this fork:

* <b>Really low CPU</b> usage on SoCs like Raspberry Pi using v4l2 grabbers
* support for multithreading for USB grabbers
* HDR/BT2020 color & gamma correction
* LUT table generator with import feature

<b>Before and after on some HDR/BT2020 content that was broken by the video grabber:</b>
<img src='https://i.postimg.cc/SRdv0VFd/compare0.png'/>
<img src='https://i.postimg.cc/7PncTPGz/compare1.png'/>
<img src='https://i.postimg.cc/9FXkP3Zn/compare2.png'/>

<br/><b>Configuration:</b>
<img src='https://i.postimg.cc/prymCNLj/screenshot8.png'/>

<br/><b>Lut table generator:</b>
<img src='https://i.postimg.cc/mgVhv219/lutgenerator.png'/>

## License
The source is released under MIT-License (see http://opensource.org/licenses/MIT).<br>
[![GitHub license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://raw.githubusercontent.com/hyperion-project/hyperion.ng/master/LICENSE)
