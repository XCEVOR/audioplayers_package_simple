# audioplayers_package_simple

The purpose of this project is to quickly implement audio file playback in Flutter using the most basic function of the "audioplayers" package.

## Getting Started

Based on Flutter's default creation app, apply three bundles of code and check the audio file playback.</br>
<pre>
Step 1.
import 'package:audioplayers/audioplayers.dart';

Step 2.
  AudioPlayer audioPlayer = AudioPlayer();

Step 3.
            IconButton(
              onPressed: (() async {
                await audioPlayer.play(AssetSource('LOCAL PATH'));
              }),
              icon: Icon(Icons.play_arrow),
            ),
</pre>

<img height="600" src="https://user-images.githubusercontent.com/111336041/201357534-f8bdfdb1-147e-4b5a-97dd-2576d9889e33.gif"/>
