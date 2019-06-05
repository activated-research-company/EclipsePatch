# EclipsePatch

Skeleton patch structure for the ARC Eclipse, based off of <a href="https://github.com/twinearthsoftware/ArduinoSketchUploader">Arduino Sketch Uploader</a>

Process for creating a patch:

<ul>
  <li>
    Pull down source files.
  </li>
  <li>
    Rename folder to "ARC Eclipse Patch v[Version]" where [Version] is the version number of the patch.
  </li>
  <li>
    Compile source code to hex. If using the Arduino IDE this is done via Sketch -> Export Compiled Binary, or Ctrl + Alt + S, and is saved to the sketch directory.
  </li>
  <li>
    Copy to source code to the Sketch folder, located inside the patch folder.
  </li>
  <li>
    Zip the patch folder.
  </li>
</ul>

Patches can be sent to customer along with the instructions to apply the patch.
