# EclipsePatch

Skeleton patch structure for the ARC Eclipse, based off of <a href="https://github.com/twinearthsoftware/ArduinoSketchUploader">Arduino Sketch Uploader</a>

Process for creating a patch:

<ul>
  <li>
    Pull down source files.
  </li>
  <li>
    Remove the Readme.md file.
  <li>
    Rename folder to "ARC Eclipse v[Version]" where [Version] is the version number of the release.
  </li>
  <li>
    Compile source code to hex. If using the Arduino IDE this is done via Sketch -> Export Compiled Binary, or Ctrl + Alt + S, and is saved to the sketch directory. The file should be named "Eclipse.ino.mega.hex".
  </li>
  <li>
    Copy to source code to the bin/Sketch folder, located inside the patch folder.
  </li>
  <li>
    Zip the patch folder.
  </li>
</ul>

Patches can be sent to customer along with the instructions to apply the patch.

Process to apply a patch:

<ul>
  <li>
    If plugged in, disconnect the power supply to your Eclipse.
  </li>
  <li>
    Connect your Eclipse to your computer via USB.
  </li>
  <li>
    Extract the zipped patch folder.
  </li>
  <li>
    Run (double-click) the Update file, this should open a progress window.
  </li>
  <li>
    Once the patch has finished the progress window will close.
  </li>
  <li>
    Wait about ten seconds for your Eclipse to reset. The screen should reset and/or blink.
  </li>
  <li>
    Disconnect the USB cable from your Eclipse and your computer.
  </li>
  <li>
    Wait ten or so seconds, then reconnect the power supply to your Eclipse.
  </li>
  <li>
    Make sure your Eclipse is functioning properly.
  </li>
</ul>
  
