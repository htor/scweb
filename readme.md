# scweb

SuperCollider in the browser. Unstable(!) Do not use for anything serious(!)

# installation

This app requires [JACK](http://jackaudio.org/) to be installed on the computer running this program. Refer to the documentation on how to install it properly. Once it's installed, run:

```
npm install
```

# starting

First, make sure JACK is running. On macOS start the JackPilot.app and hit the Start button. Then run:

```
npm start
```

Open [http://localhost:8080](http://localhost:8080) in your favourite browser.
It needs to have permission to play audio, so [give it that](https://support.mozilla.org/en-US/kb/block-autoplay)
and refresh the page. Now you can send code to SC with Cmd + Enter and get sound played back!

## cmd/ctrl+enter

evaluate code and play back sound

# license

MIT
