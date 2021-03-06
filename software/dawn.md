---
layout: api
hero-message: "Guide: Dawn"
hero-button-url: /software
hero-button: Return to Software Hub
---

<div class="container" style="max-width:1400px">
<div class="row">

<div class="col-sm-2">

	<nav id="toc" data-spy="affix" data-toggle="toc"></nav>

</div>

<div class="col-sm-10" markdown="1">

# What is Dawn?
Dawn is the software through which you can upload code to their robot and receive information. It is essentially a multi-featured app interface through which you can interact with the robot (which runs using Runtime). Dawn runs on Mac, Windows, and Linux distributions.

<img src="/assets/student-resources/dawn_guide_1.png" width="800">

## Editor
Dawn provides an editor interface, which occupies the left side of the app. Code written here can be uploaded to the robot. In addition, users can save their files, re-open them, and start new files using the File menu options, menu buttons, or the shortcuts.

### Menu Buttons
The Robot buttons include “Run”, and “Stop”. These buttons can only be used when the robot is connected. If the robot is not running, the stop button will be disabled.
The Console buttons “Console” and “Clear” serve to toggle the console element at the bottom of the editor and to clear the console output, respectively.
The Misc buttons allow you to change the font size and theme of the text editor.
The “Configuration” buttons allow you to configure the IP Address through which to connect to the robot.

### Console
A console is, generally put, a debugging interface that prints out messages from code or a receiver. The console in Dawn is responsible for displaying messages that Dawn receives from the robot (Runtime), which is essentially the output that can be expected from a running Python interpreter: print results, Python error messages, etc. Keep in mind that the robot must be connected for Dawn to receive any information to display on the console.

## Peripherals
Peripherals, located on the upper right corner, displays live sensor values collected from each sensor of a connected Robot.

Each peripheral entry corresponds to a single physical device. It will have multiple parameters such as `duty_cycle` for Yogi Bear motor controls, which refer to different values that can be read or written.

## Gamepads
Gamepads, located on the bottom right corner, displays the values received from the gamepad controller when connected to the computer. To activate the component, connect a gamepad, then press any button.

</div>

</div>
</div>
