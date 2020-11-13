# SayCheese v1.0
Take webcam shots from target just sending a malicious link

![cheese](https://user-images.githubusercontent.com/60990704/83184464-22fd5880-a147-11ea-924a-e8af8d80a73a.jpg)

# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

<p>The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types. </p>

[See more about MediaDEvices.getUserMedia() here](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
<p> To convince the target to grant permissions to access the cam.</p>
<p> All for ethical purposes, I am not responsible for misuse, if they use it without consent it is illegal and they can go to jail. </p>

## Installing (Kali Linux/Termux):

```
git clone https://github.com/Hacking-y-Pentest/Saycheese-By-thelinuxchoise

cd saycheese

apt-get install wget

apt-get install php

bash saycheese.sh
```

