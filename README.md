# beatdetection
Experiment to create beat detection algorithm in cables.gl

## Usage

The patch uses the MicrophoneIn operator to get audio input.

### Go to the visualizer page 
Open a browser and go to the [Patch](https://cables.gl/p/2ESFH8).

### Accept michophone usage
Accept that the browser want to use the microphone, e.g. click on "Allow". 
The visualizer will render stuff based on the sound from the computer microhone.

### Start the music
So start to play some music on your computer, e.g. open a browser and start playing the SHS31 mix from YouTube or SoundCloud:
[SHS31](https://soundcloud.com/rafaelcalazans/shs-31-lady-starlight-x-rodhad-x-speedy-j-live-160k/).

### Start patch
Press play on the play button to start the patch.

## Output
The patch renders a graph and three circles:
- The graph is the FFT audio analyzer array
- The gray circle is the audio analyzer avg. volume
- The green circle is beat detection algorithm #1
- The blue circle is beat detection algorithm #2

If you can help to improve the detection algorithms please let me know.
