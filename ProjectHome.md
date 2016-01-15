<h4>Concept</h4>
A tool to encode and decode bits into analog audio. Does so by performing a fast fourier transform on the audio file and then modifying a high, inaudible frequency -- thereby encoding data. The encoder does not encode the message into the digital data in the audio file but encodes it into the actual <b>sounds</b>.
<h5>Developing</h5>
<p>
You can test the project by downloading the compiled jar from Downloads and running the test class through <pre><code> java -jar AudioSteganography.jar [MESSAGE_TO_ENCODE] [AUDIO_PATH] </code></pre> <br />
I suggest using the test audio file, which is also provided under Downloads. It is a randomly generated .wav file of piano notes. I have not extensively tested the application with any other types of recordings. <br />
Developers can check out the source of the project. Netbeans project files are provided.<br>
</p>
<h5>TODO's:</h5>
  * Add classes to generate and read binary versions of non-text messages (currently only supports ASCII)
  * Test encoding audio, playing it out loud, recording it on another device, and then decoding it