# EclipsePatch

This project contains the skeleton patch structure and update commands for the [Eclipse](https://github.com/activated-research-company/Eclipse), based off of this [Arduino Sketch Uploader](https://github.com/twinearthsoftware/ArduinoSketchUploader).

## Creating a Patch

- Copy the source files from this repository.
- Remove the README.md file, .gitignore file, and git folder.
- Rename folder to "ARC Temperature Controller v[Version]" where [Version] is the version number of the release.
- Compile the Eclipse source code to hex. If using the Arduino IDE this is done via Sketch -> Export Compiled Binary, or Ctrl + Alt + S, and is saved to the sketch directory. The file should be named "Eclipse.ino.mega.hex".
- Copy to source code to the bin/Sketch folder, located inside the patch folder.
- Zip the patch folder.

Patches should be [saved as releases](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/managing-releases-in-a-repository) in the Eclipse repository. They can be sent to directly to customers along with the instructions to apply the patch. Patches are also posted on the [ARC Website](https://www.activatedresearch.com/software/arc-temperature-controller/.).

## Applying a Patch

The update process for customers is located on the [ARC Website](https://www.activatedresearch.com/software/arc-temperature-controller/.).

- If plugged in, disconnect the power supply to your Eclipse.
- Connect your Eclipse to your computer via USB.
- Extract the zipped patch folder.
- Run (double-click) the Update file, this should open a progress window.
- Once the patch has finished the progress window will close.
- Wait about ten seconds for your Eclipse to reset. The screen should reset and/or blink.
- Disconnect the USB cable from your Eclipse and your computer.
- Wait ten or so seconds, then reconnect the power supply to your Eclipse.
- Make sure your Eclipse is functioning properly. 
