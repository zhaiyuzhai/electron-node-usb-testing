# electron-node-usb-testing
Testing node-usb with electron framework
This is simple cross platform app made with electron framework using node-usb. This app gives the list of usb devices currently connected.
To test it using electron rebuild the project<br>
<code>npm rebuild --runtime=electron --target=1.6.2 --disturl=https://atom.io/download/atom-shell --build-from-source</code>

To build the packages, install electron-packager npm module<br>
<code>electron-packager electron-node-usb electron-node-usb --platform=linux --arch=x64 --electron-version=1.6.2</code>

For OSX, platform=darwin
For Windows, platform=win32

Packaged app here https://goo.gl/bqUClN

<img src="img.png">
